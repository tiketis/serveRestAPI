# Bootcamp #01 Qualiters Club
Teste de API Rest do manual a CI/CD
## O que é
Este repositório foi criado para o bootcamp de Teste de API Rest.
## Tecnologias utilizadas
- Postman versão web
- node version v20.9.0
- newman version 6.0.0
- newman-reporter-htmlextra version 6.0.0
## Documentações
- Analise Técnica: Analise/
- Doc da API: [Consulte Swagger](https://serverest.dev/#/)
## Como instalar o ambiente
- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-htmlextra
](https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm install -g newman-reporter-htmlextra
```
## Como rodar os testes
### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada
### Pelo newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os teste com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```
### Report
Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html, com o resultado dos testes e para verificar as validações, você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.
## Entre em contato
email: tiketis@hotmail.com

linkedin: https://www.linkedin.com/in/thiago-oliveira-de-almeida-78a98721/
