# 📚 Livraria Online

Sistema web para gerenciamento e venda de livros, permitindo cadastro de produtos, controle de clientes e realização de vendas de forma simples e eficiente.

---

## 🚀 Funcionalidades

* 📖 Cadastro e gerenciamento de livros
* 👤 Cadastro de clientes
* 🛒 Sistema de vendas
* 🔍 Busca de livros por título, autor ou categoria
* 📊 Dashboard administrativo
* 💰 Controle de estoque
* 🧾 Histórico de pedidos

---

## 🛠️ Tecnologias Utilizadas

* **Backend:** Django / Python
* **Frontend:** HTML, CSS, JavaScript
* **Banco de Dados:** SQLite / PostgreSQL
* **Controle de versão:** Git e GitHub

---

## 📂 Estrutura do Projeto

```
livraria/
│
├── core/                # Configurações principais do projeto
├── books/               # App de gerenciamento de livros
├── customers/           # App de clientes
├── sales/               # App de vendas
├── templates/           # Arquivos HTML
├── static/              # CSS, JS e imagens
├── db.sqlite3           # Banco de dados
└── manage.py            # Gerenciador do Django
```

---

## ⚙️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/livraria.git
cd livraria
```

### 2. Crie um ambiente virtual

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute as migrações

```bash
python manage.py migrate
```

### 5. Crie um superusuário

```bash
python manage.py createsuperuser
```

### 6. Inicie o servidor

```bash
python manage.py runserver
```

Acesse: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🔐 Acesso ao Sistema

* Área administrativa: `/admin`
* Utilize o superusuário criado para login

---

## 📸 Screenshots (Opcional)

Adicione imagens do sistema aqui:

```
/static/images/screenshot1.png
```

---

## 📌 Melhorias Futuras

* Integração com meios de pagamento
* Sistema de avaliações de livros
* Recomendação de livros por perfil
* API REST para integração com apps mobile
* Deploy em nuvem (AWS, Heroku, etc.)

---

## 🧪 Testes

Para executar os testes:

```bash
python manage.py test
```

---

## 📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar e modificar.

---

## 👨‍💻 Autor

Desenvolvido por **[Seu Nome]**
📧 Contato: [seu-email@email.com](mailto:seu-email@email.com)
🔗 GitHub: [https://github.com/seu-usuario](https://github.com/seu-usuario)

---