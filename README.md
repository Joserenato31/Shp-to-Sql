# Shp-to-Sql
Código utilizado para adicionar os Shps para o banco de dados

Para rodar perfeitamente subistitur o diretorio da pasta no campo PATH

Subistituir também as informações do cmd conforme o código a baixo ( varia de ambiente para ambiente).
'set PGPASSWORD=<senha> shp2pgsql -W "LATIN1" -s 4326 "<nome do shp>" <nome tabela> | psql -U <usuario> - d <database>'
