Aqui você encontra algumas dicas e instruções sobre como usar o Git e o GitHub!


### CONCEITO DE GIT
O Git é um sistema de versionamento de projetos que pode ser usado para salvar as alterações de seu projeto dentro de um repositório e manipulá-las através do tempo


### CONCEITO DE GITHUB
O GitHub é uma nuvem de repositórios online que pode armazenar seus projetos dentro de repositórios remotos, públicos ou privados, e estes podem ser acessados e editados facilmente pelos contribuintes do projeto


### CONCEITO DE COMMITS E BRANCHES
Assim que o seu projeto é armazenado dentro de um repositório, ele passa a seguir a linha do tempo principal, a qual chamamos de BRANCH MASTER. Dentro dela podem haver diversos pontos de alteração, os COMMITS. E, assim como em um multiverso, novas linhas do tempo (BRANCHES) podem ser criadas para dentro delas serem armazenadas novos COMMITS que não interfiram na BRANCH MASTER ou em qualquer outra já criada

Com essa funcionalidade incrível é possível recuperarmos atualizações antigas e comparar versões novas com anteriores, além de usar outras ferramentas, como unificar duas branches em uma só considerando as informações dentor de cada uma


### PRIMEIROS PASSOS
Instale o Git em sua máquina e, dentro na pasta do seu projeto, inicialize o Git Bash, um terminal que fará com que a mágica aconteça!


### git init
Inicializa um repositório Git dentro da pasta.


### git add <file>
Acrescenta um determinado arquivo para a fila de espera a ser commitada


### git add .
Acrescenta todos os arquivos dentro do repositório para a fila de espera a ser commitada


### git commit -m "o que você fez"
Cria um novo ponto na linha do tempo apresentando o que e quando foi feito


### git push
Envia todos os commits criados para o repositório


### git branch -M "algum nome"
Renomeia o nome da branch principal


### git checkout -b "new branch"
Cria uma nova branch e muda para ela automaticamente

### git pull
Atualiza seus arquivos para a última versão do repositório
