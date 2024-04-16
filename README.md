## Tech Chalenge #1
Repositório com objetivo de atender aos requisitos propostos no projeto integrador do curso de Machine Learning Engineering da instituição FIAP.

## Tecnologias utilizadas
- Python
- FastAPI
- Swagger
- Docker

## Requisitos
- Docker
- Docker Compose

## Make commands
Utilize os comandos abaixo para executar as ações desejadas:

**Iniciar aplicação localmente**

```
make init
```

**Instalar depêndencias do projeto**

```
make setup
```

**Limpar cache**

```
make clean
```

## Documentação
Com o projeto rodando localmente, basta acessar o link para consultar a documentação do projeto:

http://localhost:8000/docs
****

## Agenda evolutiva do projeto:
- [x] Endpoint GET /producao
- [ ] Endpoint GET /processamento ***(Necessário corrigir "parseamento" do payload de response)***
- [x] Endpoint GET /comercializacao
- [x] Endpoint GET /importacao
- [x] Endpoint GET /exportacao
- [ ] Acrescentar Payloads de Request e Response na Documentação do Swagger
- [ ] Continuous Deploy
- [ ] URL pública para API (AWS Lambda)
- [ ] Implementar Método de Autenticação (JWT)

# Testes
Após o container subir a api, basta realizar uma requisição nos diferentes endpoints que a api oferece. O notebook "testes.ipynb" contém todos os testes para serem executados apenas rodando as células.