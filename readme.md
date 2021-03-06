### git add <NOME_ARQUIVO>
  
  Serve para adicionar as nossas mudanças
  na área de stage

### git restore <NOME_ARQUIVO>
  
  Serve para restaurar uma mudança feita no arquivo.

### git commit -m "<MENSAGEM_PARA_ALTERAÇÃO>"
  
  Serve para criar uma mensagem de identificação
  das alterações feitas naquele momento

### git restore --staged <NOME_ARQUIVO>
 
  Serve para restaurar um arquivo da área de stage
  (área para commit)

### git restore <NOME_ARQUIVO>
 
  Serve para desfazer alterações em arquivos que não estão 
  na área de stage

### git status
 
  Serve para nós visualizarmos o estado atual
  do nosso repositório local


### git merge <NOME_DA_BRANCH>
  Serve para mesclar os códigos da branch ATUAL, com 
  a branch que tem o nome no comando

---

### git checkout -b <NOME_BRANCH>
  Serve para criarmos uma "cópia" a partir de uma
  determinada branch, para que possamos trabalhar
  tranquilamente.

### git branch --all
  Serve para listar todas as branchs que nós temos
  atualmente no nosso repositório


### git checkout <NOME_BRANCH> || <ID_COMMIT>
  Serve para navegarmos entre branchs do projeto e caso
  passarmos o id de um commit, voltamos para o código
  naquele commit.


### git branch -D <NOME_BRANCH>
  Serve para deletarmos uma branch local


### git add . 
  Serve adicionarmos todas as mudanças
  na área de stage

---


### git branch -m <NOME_NOVA_BRANCH>
  Serve para alterar o nome da branch atual

### git remote add origin <NOME_ORIGIN_GITHUB_POR_EXEMPLO>
  Serve para vincularmos o nosso repositório local
  com um repositório remoto, fazendo assim com que nosso
  repositório esteja "hospedado"
  
### git push -u origin <NOME_BRANCH>
  Serve para enviarmos a nossa branch local para o repositório
  remoto, isso tem que ser feito sempre que uma nova branch é criada.


### git push 
  Serve para enviarmos a nossa branch local para o repositório
  remoto, mas funciona somente para branchs que já estão no repositório
  remoto anteriormente.

---

### git log
  Serve para visualizarmos o log de commits e alterações.


### git pull
  Serve para obter as informações que não estão no seu repositório local.

---

### git revert <HEAD~2> || <ID_COMMIT>
  Serve para reverter e criar um novo commit baseado no commit revertido.

### git reset <HEAD~3> || <ID_COMMIT>
  Serve para resetar os nossos commits, porém perde o histórico dos commits
  posteriores.

---

### git diff <NOME_ARQUIVO>
  Serve para mostrar a diferença entre o código atual
  e o código anterior, mostrando o que foi removido e/ou
  adicionado.

---

### git stash 
  Serve para adicionar as mudanças atuais na área de stash,
  que pode ser aplicado futuramente

### git stash list
  Serve para listar todos os nossos stashs criados

### git stash apply
  Serve para aplicar os stash que estão na área de stash

### git stash clear
  Serve para limpar a pilha de stashs

### git stash push -m "<MENSAGEM>
  Serve para criar um stash com uma mensagem 
  personalizada.

### git stash apply <stash@{n}>
  Serve para aplicar um stash específico,
  baseado na pilha de stashes

### git stash pop <stash@{n}>
  Serve para aplicar um stash específico,
  baseado na pilha de stashes e remover esse
  stash citado no comando.
