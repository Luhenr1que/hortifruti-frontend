# 🎨 Hortifruti Premium - Frontend

Este é o cliente web estático para o Hortifruti Premium, desenvolvido utilizando HTML, CSS, JavaScript (Fetch API) e Bootstrap. Ele se conecta à API do backend para exibir a vitrine, detalhes de produtos, carrinho de compras e área administrativa.

## 📁 Estrutura de Pastas
- `css/style.css`: Arquivo de estilo visual do projeto.
- `js/config.js`: Define o endereço da API (`const API_URL = "http://127.0.0.1:5000";`).
- `js/layout.js`: Gerenciador comum de layout (Navbar, Footer, Modal do Carrinho, lógica de autenticação).
- `index.html`: Vitrine de produtos.
- `produto.html`: Detalhes do produto.
- `login.html` / `registrar.html`: Páginas de login e registro de usuários.
- `admin.html` / `admin_produtos.html` / `editar.html`: Área administrativa para gerenciamento de produtos.

## 🚀 Como Executar
Por ser um site estático, você pode rodá-lo localmente de duas formas:
1. **Abrir diretamente**: Dê dois cliques em `index.html` para abrir no seu navegador.
2. **Servidor Local Estático (Recomendado)**:
   - Utilizando a extensão **Live Server** do VS Code.
   - Ou utilizando o Python na pasta `frontend/`:
     ```bash
     python -m http.server 8000
     ```
     Depois acesse `http://localhost:8000`.

*Nota: Certifique-se de que a API Backend está ativa e rodando na porta correta (padrão 5000).*
