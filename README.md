# Integracao-Node-GoogleSheets-API

## Sobre o Projeto

O projeto **Integracao-Node-GoogleSheets-API** é uma aplicação Node.js que automatiza a extração de dados de uma planilha do Google Sheets e o envio desses dados para uma API REST, demonstrando a integração entre diferentes plataformas de serviços na nuvem.

### Funcionalidades

- **Autenticação via `JWT`**: Utiliza um JSON Web Token para autenticação segura com a Google Sheets API, permitindo o acesso programático à planilha.
- **Leitura de Dados**: Emprega a biblioteca `google-spreadsheet` para acessar e ler dados de uma planilha específica do Google Sheets.
- **Transformação de Dados**: Converte as linhas da planilha em objetos JSON, preparando-os para serem enviados para uma API externa.
- **Envio de Dados para API REST**: Realiza requisições POST para uma API REST, enviando os dados processados para serem utilizados em outras aplicações ou serviços.

### Tecnologias Utilizadas

- **Node.js**: Como ambiente de execução server-side.
- **Google Sheets API**: Para interação com planilhas online.
- **Fetch API**: Para realizar requisições HTTP.
- **JavaScript ES6+**: Para um código mais conciso e moderno.

### Execução do Projeto

O script é executado via linha de comando, iniciando o fluxo de autenticação, leitura, transformação e envio dos dados de forma automatizada.

### Contribuições

Contribuições são bem-vindas para melhorar ou adicionar novas funcionalidades ao projeto.

### Licença

Este projeto está sob a licença MIT.




