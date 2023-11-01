<h1 align="center"> Sistema de gerenciamento de livros </h1>

<p align="center">Aplicação desenvolvida MVP(Minimum Viable Product) para resolução de um problema apresentado pelo Senai no curso técnico em Desenvolvimento de Sistemas. O projeto é um CRUD simples no padrão arquitetura MVC(Model-View-Controller) relacionado a livros.
 <br/>
</p>


## 💻 Projeto

O principal objetivo deste projeto é fornecer uma solução básica para a gestão de livros. É uma ferramenta que permite aos usuários:

- Inserir informações de novos livros, como título do livro, nome do autor, ISBN e editora.
- Editar informações de livros existentes.
- Listar todos os livros armazenados no banco de dados.
- Excluir livros do banco de dados.



### 📋 Pré-requisitos

Antes de executar a aplicação, é necessário configurar o ambiente. Certifique-se de que o seguinte está instalado e configurado em sua máquina:

- Java Development Kit (JDK)
- MySQL Server
- IDE de sua escolha (Eclipse, IntelliJ IDEA, etc.)
- Maven (gerenciador de dependências)

Além disso, você precisará criar um banco de dados MySQL para armazenar as informações dos livros. O script SQL para a criação do banco pode ser encontrado no diretório sql deste projeto.

## 📦 Implantação

Para implantar o sistema em um ambiente de produção, você precisará de um servidor web compatível com aplicativos Spring Boot. Consulte a documentação do Spring Boot para obter mais informações sobre implantação.


### 🔧 Instalação

Aqui estão os passos para configurar o ambiente de desenvolvimento:

Clone o repositório para sua máquina local:

git clone https://github.com/IsabellyAquino/SA-livros.git

## Executando a aplicação

Importe o projeto para a IDE de sua escolha.

Configure as informações de conexão com o banco de dados no arquivo src/main/resources/application.properties.

Execute a aplicação selecionando o arquivo Situacao4Application.java e executando a aplicação.

Abra um navegador da web e acesse a interface de usuário (geralmente, em http://localhost:8081/livro).


## 🛠️ Tecnologias Utilizadas

- Linguagem de programação: Java
- Padrão de arquitetura: MVC (Model-View-Controller)
- Framework: Spring Boot
- Framework Web: Spring Web
- Framework de persistência: Spring Data JPA
- Frontend: Thymeleaf, Bootstrap, HTML e CSS
- Banco de dados: MySQL
- IDE: IntelliJ
