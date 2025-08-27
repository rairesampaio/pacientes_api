# Esse é meu primeiro projeto. Foi feito com auxílio de ChatGPT, apenas para fins de estudo, sem qualquer valia para avaliações
# API de Pacientes 🏥

Projeto simples de **CRUD com FastAPI + SQLite** para gerenciamento de pacientes.

## 🚀 Tecnologias
- Python 3.10+
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic

## 📂 Estrutura
app/
├── main.py
├── database.py
├── models.py
├── schemas.py
├── crud.py
└── routes.py


## ▶️ Como rodar o projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/pacientes_api.git
   cd pacientes_api

2. Crie um ambiente virtual e instale as dependências
```
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

4. Execute o Servidor
uvicorn app.main:app --reload

5. Acesse a documentação
http://127.0.0.1:8000/docs

📌 Endpoints

POST /pacientes/ → cria paciente

GET /pacientes/ → lista todos

GET /pacientes/{id} → busca por ID

PUT /pacientes/{id} → atualiza paciente

DELETE /pacientes/{id} → remove paciente
