Workshop de Git 2024
======================

por [Bernardo Quaresma](mailto:bernardo@tegraf.puc-rio.br)


O que é?
--------

Git é uma ferramenta para gerenciamento distribuído de versões de um projeto composto por conjunto de arquivos e pastas.

Cada modificação em um ou mais arquivos gera uma nova versão do projeto que possui uma apontamento de diferenças para a versão anterior.

O gerenciamento do projeto é considerado distribuiído porque pode ser feito em ramos e máquinas independentes.

Além de armazenamento e versionamento dos arquivos do projeto, o Git oferece uma forma de incorporar modificações feitas no mesmo arquivo de ramos independentes em um ramo principal.


Porque Git?
-----------

A possibilidade de desenvolver e testar novas funcionalidades e melhorias de forma distribuíde e independente facilita a divisão e planejamento do trabalho.

Além disso, infraestruturas como GitHub e GitLab oferecem ferramentas de criação e atribuição de pendências (issues) que dinamizam o gerenciamento de projetos com equipes distribuídas.

Finalmente, com o Git é possível desenhar um fluxo de trabalho comum que reduz a necessidade de comunicação instantânea entre os integrantes do projeto.


Como Usar?
----------

  - Repositórios Remotos x Locais
  - Acessando o repositório de um projeto remoto (GitHub)
  - Criando um Repositório local (Clone)
  - Ramificando o desenvolvimento (Branch)
  - Modificando o ramo local (Stage/Commit)
  - Atualizando o repositório remoto (Push)
  - Integrando os Ramos de Desenvolvimento (Pull/Merge Request)


Exercício
---------

1. Repliquem este projeto (Fork) no GitHub
2. Dividam os tópicos da próxima seção entre vocês
3. Clonem o projeto replicado na máquina de vocês
4. Criem ramos locais nomeando com um breve descrição da pendência que estão resolvendo (Ex: Formatacao)
5. Preencham o tópico atribuído para você (vale consulta)
6. Modifiquem o ramo local com as alterações incluindo uma mensagem que a descreva
7. Atualize o repositório remoto com o ramo criado


Markdown
--------

Markdown é uma forma de escrever arquivos texto seguindo regras que serão seguidas para exibição do texto com formatação.

### Formatação

#### Itálico
Para formatar o texto em itálico é utilizado um * (asteristicos) no início e no fim da palavra/frase.
Por exemplo: *Esse texto está em itálico*

#### Negrito
Para formatar o texto em itálico é utilizado dois ** (asteristicos) no início e no fim da palavra/frase.
Por exemplo: **Esse texto está em negrito**

#### Bloco de Código

### Listas

#### Listas Numeradas

Para criar listas numeradas, comece uma linha com 1. ou 1).

Exemplo:
1. Vivi
1. Hanna
1. Dani
1. Judy

#### Listas com subitems 

Para criar listas de itens, comece uma linha com * ou - ou +.

Exemplo:
- uva
- banana
- maçã
- morango

#### Listas de Tarefas

Para criar listas de tarefas, comece uma linha com - [ ] e, caso queira marcar adicione um "x" dentro dos colchetes.

Exemplo:
- [ ] Crepúsculo
- [ ] Batman
- [x] 10 coisas que eu odeio em você

### Tabelas

SINTAXE CLÁSSICA

Para definir uma tabela, use as seguintes regras:

- Separe colunas com barras verticais (|)
- Insira barras verticais (|) em ao início e fim da tabela
- Separe o título das colunas do conteúdo com uma linha de demarcação contendo pelo menos três traços (-)


| Nome | Curso |
| --- | ---- |
|Dani  |   CC  |
|Hanna |   CC  |
|Judy  |   CC  |
|Vivi  |   EC  |


ALINHAMENTO

Para alinhar o conteúdo de uma coluna inclua dois pontos (:) antes ou depois do traço de demarcação do lado que deseja alinhar. Se deseja centralizar o conteúdo, use os dois pontos em ambos os lados.

| Nome | Curso |
|:---- |:-----:|
|Dani  |   CC  |
|Hanna |   CC  |
|Judy  |   CC  |
|Vivi  |   EC  |


Anotações
---------

Usem esse espaço para manter uma lista de anotações e dicas como comandos do Git, links do GitHub e exemplos de Markdown.

1.



