# Fazer upload do código para um repositório do GitHub

* Acessar o GitHub e criar um novo repositório (linux-web-server-iac)
* Acessar a pasta local com os aquivos a serem enviados para o GitHub
* Executar os comandos abaixo no terminal
`git init`
`git branch -m master main`
`git add .`
`git commit -m "IAC - Instalação do servidor Apache"`
`git branch -M main`
`git remote add origin https://github.com/edi-2/linux-web-server-iac.git`
`git push -u origin main`