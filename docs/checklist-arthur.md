| Inspetor(a)      | Taynara de Jesus Carvalho |
|------------------|---------------------------|
| Data de Inspeção | 12/10/2018                |


| ARTEFATO            | ID QUESTÃO | SIM | NAO | INDEFINIDO | OBSERVAÇÕES                                                        | DEFEITOS                                                                                           |
|---------------------|------------|-----|-----|------------|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| DER                 | 1          |  X   |    |            |                                                                    |                                                           |
| DER                 | 2          |     | X   |            |                                                                    | Falta id nas entidades de “Perfumaria” e “Receita”                                                                              |
| DER                 | 3          | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 4          | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 5          |    | X    |            |                                                                    |                                          A relação “Comercializa” não apresenta sentido do fluxo                                                          |
| DER                 | 6          |     | X   |            |                                                                    | A relação “Comercializa” possui nome confuso                              |
| DER                 | 7          |     | X   |            |                                                                    | Falta a chave do pai nas entidades “Perfumaria” e “Medicamento” |
| DER                 | 8          | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 9          |    |   X  |            |                                                                    |        O atributo "quantidade" se repete entidades “Perfumaria” e “Medicamento”                                                                                            |
| DER                 | 10         | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 11         | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 12         | X   |     |            |                                                                    |                                                                                                    |
| DER                 | 13         | X   |     |            |                                                                    |                                                                                                    |
| Diagrama Lógico     | 1          |    |  X   |            |                                                                    | 	A cardinalidade entre “Medicamento” e “Receita” difere nos dois diagramas             |
| Diagrama Lógico     | 2          |     | X   |            |                                                                    |                       Falta chave primária na entidades de “Receita”, “Perfumaria”, “telefone” e “comercializa”                                                                             |
| Diagrama Lógico     | 3          | X   |     |            |                                                                    |                                                                                                    |
| Diagrama Lógico     | 4          |     | X   |            |                                                                    |  A cardinalidade entre “Medicamento” e “Receita” difere nos dois diagramas                                                           |
| Diagrama Lógico     | 5          | X   |     |            |                                                                    |                 As entidades “telefone” e “comercializa” não começam em letra maiúscula                                                                                   |
| Diagrama Lógico     | 6          |    |  X   |            |                                                                    |    o atributo “qualidade” é repetido nas entidades “Produto” e “Venda”                                                                                                |
| Diagrama Lógico     | 7          |  X   |    |            |                                                                    |                                                   |
| Diagrama Lógico     | 8          | X   |     |            |                                                                    |                                                                                                    |
| Diagrama Lógico     | 9          |    |  X   |            |                                                                    |           A maioria dos atributos não possuem o nome da Entidade                                                                                         |
| Diagrama Lógico     | 10         |   X  |     |           |                          |                                                                                                    |
| Diagrama Lógico     | 11         |   X  |    |            |                            |
| Dicionário de Dados | 1          | X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 2          | X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 3          | X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 4          | X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 5          | X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 6          |  X   |    |            |                             |
| Dicionário de Dados | 7          |  X   |     |            |                                                                    |                                                                                                    |
| Dicionário de Dados | 8          |     | X   |            |                                                                    | Falta chave primária na entidade de “telefone”, “Perfumaria” e “Receita”                                        |