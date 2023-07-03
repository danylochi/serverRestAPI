# Bootcamp Qualiters club serverRestAPI
Criação de testes de Api utilizando postman, newman e newman-htmlextra

## O que é
Repositório criado para o bootcampo de Testes de API Rest

## Tecnologias
- Postman
- node v16.13.1
- newman v5.3.0
- newman-reporter-html

## Documentações
- Doc da API: [Consulte Swagger](https://serverest.dev/).

## Como instalar o ambiente
- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
  ```
  npm install -g newman
  ````
 
- Terceiro: realize a instalação da dependencia dos relatórios (opcional)([newman#html-reporter](https://www.npmjs.com/package/newman#html-reporter)
```
    npm install -g newman-reporter-html
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
Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta  newman que foi criada no local em que os arquivos de collection e environment se encontram.

### Entre em contato
____________________________________________________________________________________________________________________________________________
[LinkedIn](https://www.linkedin.com/in/dayanecdomingues/)
