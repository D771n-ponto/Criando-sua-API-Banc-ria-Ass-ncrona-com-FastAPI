# WorkoutAPI 

Projeto de uma API assíncrona para gerenciamento de competições de Crossfit, desenvolvido durante o bootcamp da DIO em parceria com a Luizalabs.

##  Tecnologias Utilizadas
* **Python 3.11+**
* **FastAPI** (Framework web moderno e rápido)
* **Pydantic** (Validação de dados)
* **SQLAlchemy** (ORM para banco de dados)
* **Alembic** (Migrações de banco de dados)
* **Docker** (Para rodar o banco de dados PostgreSQL)

##  Principais Desafios Superados
1. **Programação Assíncrona:** Implementação de endpoints que não bloqueiam a execução.
2. **Modelagem de Dados:** Criação de relações entre Atletas, Categorias e Centros de Treinamento.
3. **Tratamento de Erros:** Respostas customizadas para erros de integridade (como CPF duplicado).

##  Como rodar o projeto
1. Clone o repositório: `git clone https://github.com/seu-usuario/workout-api.git`
2. Crie um ambiente virtual: `python -m venv .venv`
3. Instale as dependências: `pip install -r requirements.txt`
4. Suba o banco de dados (se usar Docker): `docker-compose up -d`
5. Inicie a API: `uvicorn workout_api.main:app --reload`
