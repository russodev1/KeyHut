
# KeyHut 🏠 - Plataforma Gamer de Avaliações e Marketplace de Keys e Contas

## Visão Geral
**KeyHut** é uma plataforma web completa que conecta gamers através de avaliações de jogos e um marketplace de compra e venda de chaves de ativação (keys) e contas. É um projeto desenvolvido para demonstrar competências práticas em **frontend**, **backend** e **banco de dados relacional**, com foco em qualidade de código, design responsivo e experiência do usuário.

## Tecnologias Utilizadas
- **Frontend**: React + Vite
- **Backend**: Node.js + Express
- **Banco de Dados**: PostgreSQL (produção) / SQLite (desenvolvimento local)
- **ORM**: Prisma
- **Autenticação**: JWT (JSON Web Tokens)
- **Hospedagem**: Vercel (frontend) | Render/Railway (backend e banco)

## Funcionalidades
- Cadastro e Login de Usuários (JWT Auth)
- Publicação e consulta de **reviews** de jogos
- Compra e venda de **keys** e **contas** de jogos
- Perfil de usuário com gerenciamento de atividades
- Filtragem avançada por gênero, plataforma e preço
- Interface **100% responsiva** com **dark mode**
- APIs RESTful seguras e performáticas

## Demonstração
> [Acesse a Plataforma Online (em breve)](#)

## Estrutura do Projeto
```
/keyhut
|-- /backend
|   |-- /src
|       |-- /controllers
|       |-- /models
|       |-- /routes
|       |-- app.js
|-- /frontend
|   |-- /src
|       |-- /components
|       |-- /pages
|       |-- /services
|       |-- App.jsx
|-- README.md
|-- package.json
```

## Como Rodar Localmente

### 1. Clone o Repositório
```bash
git clone https://github.com/seuusuario/keyhut.git
cd keyhut
```

### 2. Backend
```bash
cd backend
npm install
cp .env.example .env  # Configure o banco de dados e JWT_SECRET
npx prisma migrate dev  # Rodar migrations
npm run dev
```

### 3. Frontend
```bash
cd ../frontend
npm install
npm run dev
```

## Diferenciais da KeyHut
- 🔌 **Integração Completa** entre frontend, backend e banco de dados.
- 🌟 **UX Moderno**: responsividade, dark mode e carregamento dinâmico.
- 🔒 **Segurança**: autenticação JWT e validação de dados no backend.
- ✅ **Escalabilidade**: Estrutura modular e preparada para expansão.

## Possíveis Expansões Futuras
- Sistema de reputação de vendedores
- Mensagens diretas entre compradores e vendedores
- Integração com APIs de plataformas como Steam ou Epic Games
- Implementação de pagamento real via Stripe ou PayPal

## Contribuição
Pull requests são bem-vindos! Se quiser sugerir melhorias, fique à vontade para abrir uma issue.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---
> Desenvolvido com ❤️ por Gabriel Ferreira Alves para a KeyHut.
