# Socket Client-Server Java

Este é um projeto de um aplicativo de chat em tempo real, construído para demonstrar a comunicação full-duplex entre cliente e servidor utilizando Java com Spring Boot no backend e WebSockets no frontend.

 ## ✨ Funcionalidades

  - **Comunicação Bidirecional**: Envio e recebimento de mensagens em tempo real sem a necessidade de recarregar a página.
  - **Múltiplos Usuários**: Suporte para várias pessoas se conectarem e conversarem na mesma sala de chat.
  - **Notificações de Status**: Mensagens automáticas informam quando um novo usuário entra ou sai do chat.
  - **Interface Simples**: Frontend construído com HTML, CSS e JavaScript puro para focar na lógica do WebSocket.

## 🛠️ Tecnologias Utilizadas

### Backend

  - **Java 17**
  - **Spring Boot**
  - **Spring WebSocket**: Para a implementação do servidor WebSocket.
  - **STOMP** (Simple Text Oriented Messaging Protocol): Protocolo de sub-nível para facilitar a comunicação WebSocket.
  - **Maven**: Para gerenciamento de dependências.

### Frontend

  - **HTML5**
  - **CSS3**
    \--   **JavaScript**
  - **SockJS**: Biblioteca JavaScript para emular WebSockets em navegadores que não os suportam nativamente.
  - **StompJS**: Cliente STOMP para JavaScript, usado para se comunicar com o backend.

## 🚀 Como Executar o Projeto

Siga os passos abaixo para executar o projeto localmente.

### Pré-requisitos

  - **Java Development Kit (JDK)** - Versão 17 ou superior.
  - **Apache Maven** instalado e configurado no seu sistema.
  - Um **IDE** de sua preferência (Ex: IntelliJ IDEA, VS Code, Eclipse).

### Passos

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/KaioFerr/socket-client-server-java.git
    ```

2.  **Navegue até o diretório do projeto:**

    ```bash
    cd socket-client-server-java
    ```

3.  **Execute a aplicação Spring Boot:**

      - Você pode executar a classe principal `ChatApplication.java` diretamente pelo seu IDE.
      - Ou, use o Maven pelo terminal:

    <!-- end list -->

    ```bash
    mvn spring-boot:run
    ```

4.  **Acesse o chat no navegador:**

      - Abra seu navegador e acesse a URL: `http://localhost:8080`
      - Para simular uma conversa, abra a mesma URL em múltiplas abas ou janelas do navegador.

## 📝 Como Usar

1.  Ao abrir a página, você verá um campo para inserir seu nome de usuário.
2.  Digite um nome e clique em "Start Chatting".
3.  Você será conectado à sala de chat.
4.  Digite suas mensagens no campo inferior e pressione "Send" para enviá-las.
5.  As mensagens de outros usuários aparecerão em tempo real na tela.

