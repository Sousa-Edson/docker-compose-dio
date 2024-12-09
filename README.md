# Desafio: Hospedagem de Página Web com Docker Compose

Neste projeto, desenvolvi um ambiente Docker usando **Docker Compose** para hospedar uma página web simples. A aplicação utiliza o servidor **Apache** e serve uma página HTML com conteúdo personalizado. A página apresenta uma breve introdução com o texto "Olá Mundo!", meu nome destacado em azul, e um botão que redireciona o usuário para o meu portfólio hospedado no **GitHub Pages**.

## Detalhes do Projeto:

### Tecnologias Utilizadas:
- **Docker Compose**: Para orquestrar o container Apache.
- **Apache (httpd)**: Para servir a página HTML.
- **HTML e Bootstrap**: Para criar uma página web responsiva e estilizada.

### Funcionalidades:
- A página principal exibe uma mensagem de boas-vindas e um botão.
- O botão redireciona para o meu portfólio no **GitHub Pages**.

### Como executar:
1. Clone o repositório ou copie os arquivos fornecidos.
2. Execute o comando `docker-compose up` para iniciar o servidor.
3. Acesse a página no navegador através de `http://localhost:PORTA` (ex.: `8081`).

### Arquivos principais:
- **`docker-compose.yml`**: Configuração do container Apache.
- **`index.html`**: Página web com o conteúdo apresentado.

### Link para o portfólio:
- O botão na página redireciona para: [https://sousa-edson.github.io/portfolio/home](https://sousa-edson.github.io/portfolio/home).
