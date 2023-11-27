# Integracao-Node-GoogleSheets-API

## Sobre o Projeto

O projeto **Integracao-Node-GoogleSheets-API** é uma aplicação Node.js desenvolvida para automatizar a extração de dados de uma planilha do Google Sheets e o envio desses dados para uma API REST. Esta solução exemplifica a integração eficiente entre diferentes plataformas de serviços na nuvem.

### Funcionalidades

- **Autenticação via JWT**: Utiliza um JSON Web Token (JWT) para uma autenticação segura com a Google Sheets API, garantindo o acesso programático à planilha de forma protegida.
- **Leitura de Dados**: Implementa a biblioteca `google-spreadsheet` para acessar e extrair dados de uma planilha específica do Google Sheets, demonstrando a manipulação eficiente de dados de planilhas na nuvem.
- **Transformação de Dados**: Converte as linhas da planilha em objetos JSON, facilitando a integração e o envio de dados para sistemas externos.
- **Envio de Dados para API REST**: Utiliza a Fetch API para realizar requisições POST, enviando os dados processados para uma API REST. Isso permite que os dados sejam usados em outras aplicações ou serviços, ampliando as possibilidades de automação e integração.

### Tecnologias Utilizadas

- **Node.js**: Escolhido como ambiente de execução server-side pela sua eficiência e ampla adoção na comunidade de desenvolvimento.
- **Google Sheets API**: Para interagir com planilhas online, oferecendo uma maneira robusta e flexível de manipular dados em nuvem.
- **Fetch API**: Para realizar requisições HTTP de maneira moderna e eficaz, integrando-se facilmente com outras APIs e serviços web.
- **JavaScript ES6+**: Adotado para desenvolvimento do código, proporcionando uma escrita mais concisa e recursos modernos para um desenvolvimento ágil e eficiente.

## Como Instalar e Rodar o Projeto

### Pré-requisitos
- Node.js instalado na máquina.
- npm ou yarn para gerenciamento de pacotes.

### Instalação
1. Clone o repositório do projeto para a sua máquina local.
2. Navegue até a pasta do projeto e execute `npm install` ou `yarn install` para instalar todas as dependências necessárias.

### Executando o Projeto
- Após a instalação das dependências, execute `npm start` para iniciar a aplicação.
- A aplicação iniciará o processo de leitura da planilha e enviará os dados para a API configurada.

### Contribuições

Contribuições são bem-vindas para melhorar ou adicionar novas funcionalidades ao projeto.

## Notas Adicionais
- Este projeto foi desenvolvido como uma demonstração de habilidades em integração de APIs e automação de processos com Node.js.
- É um exemplo prático do uso de tecnologias modernas em um projeto real.

### Licença

Este projeto está sob a licença MIT.





