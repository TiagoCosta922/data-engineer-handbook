make sql
# ou diretamente:
docker exec -it my-postgres-container psql -U postgres -d postgres

Explorar a base

Ver todas as tabelas: \dt

Ver todos os schemas: \dn

Ver todas as databases: \l

Ver estrutura de uma tabela: \d table_name
Exemplo: \d actor_films

em select fechar sempre com ; no terminal para executar a query


sair do sql
\q

