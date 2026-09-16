# Chat em Tempo Real com Laravel e Pusher 💬

Este projeto é um sistema de chat em tempo real desenvolvido com WebSockets para permitir a comunicação instantânea e bidirecional entre usuários.

## 🚀 Tecnologias Utilizadas

*   **Back-end:** PHP, Laravel 11, MySQL/SQLite
*   **Front-end:** HTML, Tailwind CSS, Vite
*   **Autenticação:** Laravel Breeze
*   **WebSockets:** Pusher, pacote Chatify

## 📺 Demonstração do Projeto
(https://drive.google.com/file/d/42sSA1qkMKjsnabqjC0xSyuCmhlEK/view?usp=sharing)

## ⚙️ Como executar o projeto localmente

1. Clone este repositório: `git clone https://github.com/seu-usuario/nome-do-repo.git`
2. Instale as dependências do PHP: `composer install`
3. Instale as dependências do Node.js: `npm install`
4. Configure o arquivo `.env` com suas credenciais do banco de dados e as chaves da API do [Pusher](https://pusher.com/).
5. Execute as migrações para o banco de dados: `php artisan migrate`
6. Inicie os servidores em dois terminais simultâneos:
   * `php artisan serve`
   * `npm run dev`
