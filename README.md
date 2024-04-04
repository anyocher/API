#  👻 Avaliação formativa de PWBE 👻  

- API - Criação de API (Plataforma de Interface de Aplicação)
- CRUD - Funcionalidades de Cadastro, consulta, alteração e exclusão
- MVC - Padrão de projeto (Modelo, Visão e Controle)
- Testes - Testes unitários da API utilizando software Insomnia


### Dependencias
- mysql
- XAMPP
- MariaDB
- Apache

### Para testes

- cd api
- npm i
- npm nodemon 

|Desafio|
|-|
|A partir do script de criação e população com dados de testes do banco de dados, Desenvolva as seguintes **funcionalidades**|
|CRUD de Funcionarios: Implementar operações CRUD (Create, Read, Update, Delete) para os funcionarios|
|CRUD de Telefones: Implementar operações CRUD (Create, Read, Update, Delete) para os telefones|
|OBS: Caso deseje criar um CRUD para funcionários com telefones juntos o cliente vai ficar mais satisfeito|
|CRUD de Veiculos: Implementar operações CRUD (Create, Read, Update, Delete) para os veiculos|
|CRUD de Manutenções: Implementar operações CRUD (Create, Read, Update, Delete) para os manutenções, neste crud, nas funcionalidades READ, acrescente uma rota que mostre somente os veículos que estão em manutenção(data fim em branco ou nula)|

|Entregas|
|-|
|Repositório do Github contendo:|
|Script de criação e população do BD com dados de teste chamado script.sql em uma pasta "testes"|
|API back-end com os CRUDs no padrão MVC em uma pasta "api"|
|Arquivo insomnha.json com todas as rotas de teste na pasta "testes"|

## Como testar esta API
Necessário ter o ambiente/tecnologias acima instaladas
- 1 Clonar este repositório
- 2 Abrir com VsCode
- 3 Instalar o banco de dados
    - A Abrir o XAMPP e clicar em start no MySQL, ou iniciar o MySQL da maneira que preferir.
    - B Rodar os scripts de criação do Banco de dados e de população com dados de teste.
        - ./bd/script.sql
        - ./testes/testes.sql
- 4 Abrir um terminal **cmd** ou **bash** e navegar até a pasta ./api
```bash
cd api
```
- 5 Instalar as dependências do NodeJS
```bash
npm install
```
- 6 Executar com nodemon ou node server.js
```bash
nodemon
```
ou
```bash
npx nodemon
```
ou
```bash
node server.js
```
# 👩🏻‍💻 anyocher 👩🏻‍💻
