Github

Arquivo da aula de Git e GitHub para iniciantes

Este é um teste. Será?


**Comandos Git**


git status -> Verificar status
git add -> Adicionar ao stage
git commit -m "Mensagem" -> Commitar de fato
git log -> Mostra a hash do commit, quem executou (nome e email) e quando
    git log --author="Nome" -> Mostrar os commits de determinado autor
    git shortlog -sn -> Mostra a quantidade de commits por pessoa
git log --graph -> Mostra em forma gráfica as mudanças e versões
git show "hash" -> Mostra a alteração que foi feita naquela hash
git diff -> Mostra a mudança feita (Sempre utilizar antes de commitar)
    git diff --name-only -> Apenas o nome dos arquivos alterados 
git checkout "Arquivo" -> Vai retornar o arquivo para antes da edição
git reset HEAD -> Retira o arquivo que esteja no stage