# API Rest Spring Boot 3

API desenvolvida para Estudos na linguagem Java usando as tecnologias Sprint Boot 3 e MySql para 
persistência no banco de dados.

A API é um CRUD de médicos usando as seguintes dependências:
- Spring Boot starter Web 3.0
- Spring Boot dev tools Web 3.0
- Lombok 1.18
- Spring Boot starter Jpa 3.0
- Spring Boot starter validation 3.0
- Flyway 9.5
- Mysql Connector 8.0

## Versão 1.0
- Crud de médicos com Mysql
- Paginação de resultados com os parâmetros(pagina, tamanho e ordem)
- Controller -> /medicos
Objeto para ser enviado com Post

<code>
{
	"nome": "Chico",
	"email": "chico@voll.med",
	"crm": "888777",
	"especialidade": "ORTOPEDIA",
	"telefone": "48996723098",
	"endereco": {
    "logradouro": "rua 1",
    "bairro": "bairro",
    "cep": "12345678",
    "cidade": "Brasilia",
    "uf": "DF",
    "numero": "1",
    "complemento": "complemento"
	}
}
</code>
