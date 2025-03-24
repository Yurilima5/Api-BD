# Api de Doação de livros

Essa é uma API simples feita com Flask e SQLite3 para fins educacionais da escola vai na Web, ela permite Cadastrar e listar dados

## Como rodar o projeto

1. Faça o clone do repositório:

```bash
git clone <URL_DO_REPOSITORIO>
cd nome-do-projeto
```

2. Crie um ambiente virtual (obrigatório):
```bash
python -m venv venv
source venv/Scripts?activate
```
3. Instale as dependências
```bash
pip install -r requirements.txt
```
4. inicie o servidor:
```bash
python app.py
```
> A api está disponível em http: http://127.0.0.1:5000/

## Endpoints 

### POST /doar

Endpoints para cadastrar um novo livro

**Formato de envio dos dados**

### GET /livros

Retorna todos os livros cadastrados em nossa API.

**Resposta (200)**:
```json
{
    "id":"1",
    "titulo":"50 Tons de dívida",
    "categoria":"Finanças",
    "autor":"Fernando Polia",
    "image_url":"https://exemplo.com"
}
```

---