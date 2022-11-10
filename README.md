# DBML

O DBML é um banco de dados desenvolvido em uma estrutura de marcação, seu objetivo é ser um banco dedados simples, possibilitando uma flexibilidade para qualquer pessoa dar suporte. Sua estrutura é um mix entre datajson e esquema SQL, veja o exemplo abaixo.

```
Table users {
  id int
  name varchar
  email varchar
  pass varchar
  status varchar
}
```

O exemplo acima demonstra um exemplo de tabela, onde temos os tipos dos campos como inteiro e varchar, além dos tipos mencionados, também podemos trabalhar com outros, como: blob, text, datetime, longtext e outros encontrados no sql.
