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
    git reset --soft -> Mata o commit feito, mas o arquivo permace alterado da ultima atualização
    git reset --mixed -> Mata o commit feito, mas antes do arquivo de fato ter alterado
    git reset --hard -> Mata o commit, e tudo o que foi feito
    (Escolhe sempre o commit anterior do que deseja retornar!)
~/.ssh/ -> Encontrar a key
cat "key" -> Pegar a key
    more "key" -> Outra opção para comando acima
