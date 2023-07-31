# Usando GIT na linha de comando

### Inicialize um repositório git
    git init

### Adicione arquivos no STAGE

    git add .

### Crie um commit local
    git commit -m "Mensagem explicativa"

### Troque a branch padrão de 'master' para 'main'
    git branch -M main
    \\Este é um passo opcional e necessario apenas no primeiro acesso ao repositório

### Apontando para repositório remoto
    git remote add origin git@github.com:washingtonlopesss/GuiaComandosGIT.git
    \\Este passo é necessario apenas no primeiro acesso ao repositório

### Upload das alterações para repositório remoto
    git push -u origin main

## Alterando um commit localmente

Temos duas formas de fazer isso

1. A primeira forma de fazer isso é usando o comando:

        git reset --hard HEAD
        git reset --hard 69a3a3bce907b2ed5ddb137fdc9cc52e58640e87

    Este comando desfaz as ultimas alterações até a versão.

2. Já este comando remove o commit porem sem desfazer as ultimas alterações:

        git reset --soft HEAD
        git reset --soft 69a3a3bce907b2ed5ddb137fdc9cc52e58640e87