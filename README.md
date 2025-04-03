# Sistema de Controle de Estoque

Este é um sistema simples de controle de estoque feito com Flask + SQLite.

## Funcionalidades
- Cadastro e listagem de produtos
- Registro de movimentações (entrada/saída)
- Exportação de dados
- Login básico

## Como usar

### 1. Clone o repositório
```bash
git clone https://github.com/seuusuario/projeto-estoque.git
cd projeto-estoque
```

### 2. Crie e ative um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
```

### 3. Instale as dependências
```bash
pip install flask
```

### 4. Inicie o banco de dados
```bash
sqlite3 estoque.db < schema.sql
```

### 5. Rode o sistema
```bash
python app.py
```

Depois acesse [http://localhost:5000](http://localhost:5000)

---

## Estrutura do Projeto

- `app.py` — Arquivo principal da aplicação
- `schema.sql` — Script de criação do banco de dados
- `templates/` — HTMLs do sistema
- `static/style.css` — Estilo visual

---

### Login de Teste
Usuário: admin  
Senha: admin

---

Feito por: [Seu Nome]
