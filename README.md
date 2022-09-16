Estudando git/github - B7web

Realizando algumas modificações, para testar

Alguns comandos

git reset --soft //vai voltar ao estado antes do commit
git reset --mixed //parecido com o soft, porém volta ao estado antes do git add .
git reset --hard //vai ignorar tudo, inclusive qualquer modificação feita nos arquivos. (TESTADO) **não é recomendado ao se trabalhar em equipe**

git branch //mostra a branch atual
git branch teste //cria uma branch chamada teste
git checkout master //muda a branch atual para master (esta linha foi criada na branch teste).
git diff //mostra detalhadamente as alterações realizdas que não foram commitadas.
git diff *codigo do commit* //mostra a diff após ter feito commit na commit escolhida