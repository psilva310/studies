git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"

HEAD: Estado atual do nosso código, ou seja, onde o Git nos colocou
Working tree: Local onde os arquivos realmente estão sendo armazenados e editados
index: Local onde o Git armazena o que será commitado, ou seja, o local entre a working tree e o repositório Git em si.



https://devhints.io/git-log


NUNCA COMITAR UM CODIGO QUE NAO FUNCIONA



Alternativa correta! Com o git checkout nós desfazemos uma alteração que ainda não foi adicionada ao index ou stage, ou seja, antes do git add. Depois de adicionar com git add, para desfazer uma alteração, precisamos tirá-la deste estado, com git reset. Agora, se já realizamos o commit, o comando git revert pode nos salvar.