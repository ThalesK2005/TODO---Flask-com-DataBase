# 📝 TODO List – Flask + SQLite

Este é um projeto simples de **Lista de Tarefas (TODO List)** desenvolvido com **Flask** e **SQLite**, utilizando CRUD completo (Create, Read, Update, Delete).  
---

## 🚀 Tecnologias usadas

- **Python 3**
- **Flask**
- **Flask_SQLAlchemy**
- **SQLite**
- **HTML + CSS**
- **Jinja2**

---

## 📌 Funcionalidades

✔ Adicionar novas tarefas  
✔ Listar tarefas cadastradas  
✔ Editar tarefas existentes  
✔ Excluir tarefas  
✔ Banco de dados local SQLite  
✔ Código simples, direto e fácil de aprender  

---



## ▶️ Como rodar o projeto

1. Clone o repositório:

```sh
git clone https://github.com/ThalesK2005/TODO---Flask-com-DataBase.git

    Acesse a pasta:

cd TODO---Flask-com-DataBase

    Instale as dependências:

pip install flask flask_sqlalchemy

    Execute o servidor:

python app.py

    Abra no navegador:

http://127.0.0.1:5000

🗃 Banco de Dados

O projeto usa um banco SQLite criado automaticamente pelo SQLAlchemy:

Modelo:

class Tasks(db.Model):
    id = db.Column(db.Integer, primary_key=True)
    description = db.Column(db.String(100), unique=True, nullable=False)

🤝 Contribuições

Pull requests são bem-vindos!
Sugestões e melhorias podem ser enviadas na aba Issues.
📄 Licença

Este projeto é de uso livre para estudos.
