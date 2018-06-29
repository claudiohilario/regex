# Espressões Regulares (regex)
Apontamentos sobre expressões regulares em JavaScript.

## Ferramentas Online
  * https://regex101.com/

## Metacaracteres 
### Representantes
Metacaractere | Nome       | Função
--------------|------------|---------------------------------
`.`           |Ponto       | Representa um caractere qualquer
`[...]`       |Lista       | Representa uma lisca com os caracteres permitidos
`[^...]`      |Lista negada| Representa uma lisca com os caracteres não permitidos

### Quantificadores
Metacaractere | Nome     | Função
--------------|----------|----------
`?`           |Opcional  | Representa zero ou mais
`*`           |Asterisco | Representa zero, um ou mais
`+`           |Mais      | Representa um ou mais
`{n,m}`       |Chaves    | Representa de n até m

### Âncoras
Metacaractere | Nome             | Função
--------------|------------------|----------
`^`           |Acento circunflexo| Início da linha
`$`           |Cifrão            | Fim da linha
`\b`          |Extremos          | Inicio ou fim da palavra

### Outros
