# DadosEstudante
Teste de API CQRS com FrontEnd Angular

O teste consiste em criar uma API para adicionar, alterar, listar e excluir usuários.
TECNOLOGIAS
As tecnologias que devem ser utilizadas são:
 Microsoft .NET Core
 SQL Server
REQUISITOS
Tabela de banco de dados
 Usuarios
o Id: INTEIRO
o Nome: TEXTO
o Sobrenome: TEXTO
o Email: TEXTO
o DataNascimento: DATA
o EscolaridadeId: INTEIRO
o HistoricoEscolarId: INTEIRO
 Escolaridade
o Id: INTEIRO
o Descricao: TEXTO
 Pode ser adicionado qualquer outro campo nas tabelas caso seja necessário.

Regras de validação
 O e-mail deve ser validado.
 A data de nascimento não pode ser maior que hoje.
 A escolaridade deve permitir apenas os valores (Infantil, Fundamental, Médio e Superior)
Backend
 Criar uma API que permita adicionar, alterar, listar e excluir usuário.
 Os dados devem ser persistidos e lidos usando ORM Entity Framework ou DAPPER com banco de dados SQL
Server.
Deve disponibilizar uma Collection do POSTMAN, para consumirmos os serviços.
O QUE SERÁ AVALIADO
 Funcionamento conforme especificado;
 Arquitetura e estruturação do Backend;
 Utilização de padrões de arquitetura DDD e CQRS; - Obrigatório.
 Nomenclaturas de arquivos, variáveis e métodos;

 Validação de dados;
 Necessário praticar boas práticas e organização.
 Performance
Diferencial
Fazer o consumo da API utilizando um SPA.
