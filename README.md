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