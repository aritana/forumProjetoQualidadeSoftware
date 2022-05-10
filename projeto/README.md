Trabalho: Curso de Qualidade de Software
API: Fórum de alunos
Fonte: Curso Alura: https://cursos.alura.com.br/course/spring-boot-api-rest

ROUTES:

URL BASE: http://localhost:8080/

GET /topicos : Lista de tópicos

exemplo:
[
{
"id": 1,
"titulo": "Dúvida",
"mensagem": "Erro ao criar projeto",
"dataCriacao": "2019-05-05T18:00:00"
},
{
"id": 2,
"titulo": "Dúvida 2",
"mensagem": "Projeto não compila",
"dataCriacao": "2019-05-05T19:00:00"
},
{
"id": 3,
"titulo": "Dúvida 3",
"mensagem": "Tag HTML",
"dataCriacao": "2019-05-05T20:00:00"
}
]


GET /topicos/id : detalhes de um tópico

exemplo:
{
"id": 1,
"titulo": "Dúvida",
"mensagem": "Erro ao criar projeto",
"dataCriacao": "2019-05-05T18:00:00",
"nomeAutor": "Aluno",
"status": "NAO_RESPONDIDO",
"respostas": []
}


POST /topicos : Cadastro de tópicos

PUT /topicos/id : Alterar detalhes de um tópico

DELETE /topicos/id : Remover um tópico
