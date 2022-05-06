https://www.youtube.com/watch?v=kB5e-gTAl_s

1o. abrir o Git dentro da pasta de trabalho

2o. dar o comando Git
git init

3o. Para verificar como esta o Repositorio
git status

4o. Para adicionar arquivos no repositorio
git add "nome do codigo"

5o. Para adicionar todos os arquivo do diretorio para o repositorio
git add .

6o. inicializar o GIT
git config --global user.email "carlos.alonso@ibm.com"
git config --global user.name "carlos798"

7o. Dar Commit
git commit -m "primeiro Commit"

8o. Criar o repositorio no Git https://github.ibm.com/carlos-alonso-ibm/ClaimXJira

9o. Para enviar o código do repositorio local para a nuvem do GitHub
git remote add origin https://github.ibm.com/carlos-alonso-ibm/ClaimXJira
git push

10. A partir depois para verificar se houve qualquer modificação dar o comando:
git status

11. Para ver todas as versoes que foram dadas push
git reflog

12. Para voltar uma versão digitar:
git reset --hard "codigo da versão hash obtida no comando reflog"

13. Para ver quais branches estão disponiveis
git branch

14. Para criar uma branch
git branch "nome da Branch" ( Stagging ) 

15. para mudar de branch
git checkout "nome da Branch"

16. Para fazer merge entre 2 branches
entrar a Branch principal, dar o comando
Git pull ( para atualizar localmente a sua branch principal local ) e
depois dar o comando
git merge "nome da branch secundaria" 
e depois dar o comando
git push

17. Para criar uma branch e atualiza-la a parte da branch principal
git checkout -b "nome da Branch secundaria" "nome branch primaria"

18. Processo de Merge request
git push --> enviar para a nuvem

19. se tiver algum arquivo ou pasta que vc nao queira guardar no controle de 
versão dar o comando:
touch .gitignore
o comando acima vai criar um arquivo chamado gitignore
- entrar no arquivo com o notepad e colocar o nome dos arquivos e/ou pastas
que vc quer que o git ignore no controle de versão

