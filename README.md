### Projeto_Crud_Java_Spring_Boot

Este é um projeto de exemplo que demonstra um CRUD simples em Java usando o framework Spring Boot.

#### Funcionalidades do BackEnd

- Criação, leitura, atualização e exclusão de registros em um banco de dados.
- Utilização do padrão MVC (Model-View-Controller) para separação de responsabilidades.
- Implementação de endpoints RESTful para interação com a API.

#### Pré-requisitos

- Java Development Kit (JDK) 8 ou superior.

- Apache tomcat 10 ou superior.

- Maven para gerenciamento de dependências.

- IDE eclipse.

- Banco de Dados Postgres v9.5.

#### Configuração

1. Clone o repositório: `git clone https://github.com/wastenio/Projeto_Crud_Java_Spring_Boot.git`

2. Abra o projeto na sua IDE eclipse.

3. Instale o Banco de Dados Postgres, crie uma tabela com o nome usuario para que possa testar o projeto.

4. Configure as conexoes do banco no arquivo application.properies

#### Endpoints

| Método | Endpoint          | Descrição                   |
|--------|-------------------|-----------------------------|
| GET    | localhost:8081/springboot-rest-api-sample/listatodos     | Retorna todos os registros   |
| GET    | localhost:8081/springboot-rest-api-sample/buscarPorNome?=| Retorna um registro específico|
| POST   | localhost:8081/springboot-rest-api-sample/salvar     | Cria um novo registro        |
| PUT    | localhost:8081/springboot-rest-api-sample/atualizar| Atualiza um registro         |
| DELETE | localhost:8081/springboot-rest-api-sample/delete| Exclui um registro           |

### Criação do FrontEnd utilizando JQuery
### index.html

O arquivo `index.html` está localizado na pasta `resource/static` do projeto. Ele é responsável por fornecer a interface do usuário para interagir com a API RESTful implementada no projeto.

#### Conteúdo do arquivo

O arquivo `index.html` contém o código HTML, CSS e JavaScript necessários para criar a interface do usuário. Foi utilizado a biblioteca do bootstrap para a criação da tabela no front. Ele utiliza a biblioteca jQuery para facilitar a manipulação do DOM e a comunicação com a API.

#### Funcionalidades

- O arquivo `index.html` possui um formulário que permite ao usuário criar, atualizar e excluir registros no banco de dados.
- Ele também possui uma tabela que exibe todos os registros existentes no banco de dados.
- Através do uso de requisições AJAX, o arquivo `index.html` se comunica com os endpoints da API para realizar as operações CRUD.

#### Configuração

Para utilizar o arquivo `index.html`, certifique-se de que o projeto esteja configurado corretamente, incluindo as dependências necessárias, como o jQuery. Além disso, verifique se a API RESTful está em execução e acessível através da URL correta.

#### Observações

- É importante garantir que o arquivo `index.html` esteja localizado na pasta `resource/static` para que seja servido corretamente pelo servidor.
- Certifique-se de que as URLs dos endpoints da API estejam corretamente configuradas no arquivo `index.html` para que as requisições sejam enviadas para o local correto.

![Tela Inicial](./component/tela%20principal.png)

![Tela de Pesquisa](./component/tela%20de%20pesquisa.png)