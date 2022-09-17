Estudando git/github - B7web

Realizando algumas modificações, para testar

Alguns comandos

git reset --soft //vai voltar ao estado antes do commit
git reset --mixed //parecido com o soft, porém volta ao estado antes do git add .
git reset --hard //vai ignorar tudo, inclusive qualquer modificação feita nos arquivos. (TESTADO) *não é recomendado ao se trabalhar em equipe*

git revert --no-edit *código do commit*//reverte as alterações sem alterar o commit


git branch **mostra a branch atual**

git branch teste **cria uma branch chamada teste**

git checkout master **muda a branch atual para master (esta linha foi criada na branch teste).**

git diff **mostra detalhadamente as alterações realizdas que não foram commitadas.**

git diff *codigo do commit* **mostra a diff após ter feito commit na commit escolhida**

git diff --name-only **mostra apenas o nome dos arquivos que foram alterados**

git diff *nome do arquivo* **mostra alterações feitas no arquivo selecionado**

git checkout HEAD -- *nome do aarquivo* **remove as alterações feitas no arquivo escolhido - checkout *é pra voltar pra alguma versão de qualquer coisa - HEAD *vai para o início da branch atual* -- *sig. que tudo que vem depois é o nome de um arquivo***



//IGNORANDO ARQUIVOS .gitignore
basta criar um arquivo chamado .gitignore e dentro dele digitar o nome do arquivo a ser ignorado. *.txt ignora todos arquivos da extensão .txt 