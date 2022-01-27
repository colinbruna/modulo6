# Erro comum

- Tem uma alteração no github
- Foi feito commit direto na master
- Não foi feito pull
- Foi feita uma alteração localmente 
- Vamos tentar dar o push

##Aqui aparece o erro no terminal
- Aparece que devemos fazer um fetch primeiro, que é atualizar


Então antes de começar a trabalhar numa branch ou criar uma branch, 
sempre dar um pull para pegar a última versão do projeto

git push help

Para resolver
-git pull
-daí vão aparecer as alterações e onde está dando conflito
-Selecionamos o que é para ficar no código e fazemos o um merge, sempre que
tiver um conflito será feito um merge
git status
git add .
git commit -m ""
e agora faço git push
