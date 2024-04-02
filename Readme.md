Aprendendo a usar o Git

git init - inicialização de um repositório vazio no git

git add "arquivo para enviar" (stage) - movimenta a minha posição para o commit
git add . = todos os arquivos disponiveis são enviados

git status - verifica o status dos arquivos no git

git commit -m "Titulo do Commit" -  faz o envio das alterações feitas para o repositório, com uma mensagem explicando as modificações.
    commit:  serve para  salvar as alterações que foram feitas em um projeto.

git branch -M "main" - cria uma nova branch chamada main e torna ela como a principal do meu projeto.
    branch:  é usado para criar novas linhas temporárias de desenvolvimento dentro do projeto, ou seja, permite trabalhar em outra linha do tempo que não seja a principal.


git remote  add origin https://github.com/user/nomedapasta.git  - adiciona um novo repositório remoto

git push -u origin main - envia os commits da minha branch principal para o repositório remoto, criando a branch lá também.

