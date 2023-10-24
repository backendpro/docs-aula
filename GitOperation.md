# Operações Git

## Instalação
- A instalação do git é básica e pode seguir o seguinte padrão:
  - Buscar no google: git download
  - Baixar a versão mais recente para o seu sistema operacional
  - Next next finish

## Inicializando um Repo
- Crie um repositório normalmente na sua conta GitHub
- Siga os comandos abaixo:
  - git init: inicializa na pasta onde está o seu projeto um repositório git;
  - git add .: quando se utiliza o . significa que você está adicionando TUDO que contém na pasta e está modificado;
    - variações: é possível adicionar apenas arquivos de uma pasta especificando o caminho /src/controller ou /src/service
                 é possível adicionar um único arquivo a partir do seu caminho absoluto /src/controller/ProdutoController.java
  - git commit -m: o comando de commit significa que você está "finalizando" o processo de entrega do código
    - o parâmetro m (mensagem) deve ser seguido de uma mensagem entre aspas informando o que está sendo entregue
    - é possível utilizar -am para realizar o add + mensagem
  - git remote add origin: adicionar uma origem remota de repositório para o seu código (basicamente definir a casinha do seu código fora sua máquina)
  - git push: finaliza de vez a entrega do código (commit) no repositório remoto

## Comandos Git

- git status: comando que informa qual branch está usando e qual o estado atual da sua branch
- git branch <NOME_BRANCH>: esse comando serve para criar uma ramificação do código principal
