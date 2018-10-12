| Inspetor(a)      | Vinícius de Castro Cantuária |
|------------------|---------------------------|
| Data de Inspeção | 12/10/2018                |

| ARTEFATO            | ID QUESTÃO | SIM | NAO | INDEFINIDO | OBSERVAÇÕES                                         | DEFEITOS                                                                               |
|---------------------|------------|-----|-----|------------|-----------------------------------------------------|----------------------------------------------------------------------------------------|
| DER                 | 1          | x   |     |            |                                                     |                                                                                        |
| DER                 | 2          |     | x   |            | Medicamento tem ID desnecessário                    | Receita não possui ID                                                                  |
| DER                 | 3          | x   |     |            |                                                     |                                                                                        |
| DER                 | 4          | x   |     |            |                                                     |                                                                                        |
| DER                 | 5          |     | x   |            |                                                     | Fluxo de Venda comercializa Produto                                                    |
| DER                 | 6          | x   |     |            | Nome comercializa poderia se substituido por possui |                                                                                        |
| DER                 | 7          |     | x   |            |                                                     |                                                                                        |
| DER                 | 8          | x   |     |            |                                                     |                                                                                        |
| DER                 | 9          |     | x   |            |                                                     | Produto e Venda possuem o atributo quantidade com mesmo nome                           |
| DER                 | 10         | x   |     |            |                                                     |                                                                                        |
| DER                 | 11         | x   |     |            |                                                     |                                                                                        |
| DER                 | 12         | x   |     |            |                                                     |                                                                                        |
| DER                 | 13         | x   |     |            |                                                     |                                                                                        |
| Diagrama Lógico     | 1          |     | x   |            |                                                     | A cardinalidade entre Medicamento e Receita são diferentes                             |
| Diagrama Lógico     | 2          |     | x   |            |                                                     | Muitas entidades possuem apenas chaves secundárias                                     |
| Diagrama Lógico     | 3          | x   |     |            |                                                     |                                                                                        |
| Diagrama Lógico     | 4          |     | x   |            |                                                     | Muitas cardinalidades sem sentido, como as da herança                                  |
| Diagrama Lógico     | 5          |     | x   |            |                                                     | Alguns estão em caixa alta e outros em caixa baixa                                     |
| Diagrama Lógico     | 6          |     | x   |            |                                                     | Há nomes de atributos repetidos, e o nome de tabela "comercializa" não é significativo |
| Diagrama Lógico     | 7          | x   |     |            |                                                     |                                                                                        |
| Diagrama Lógico     | 8          |     | x   |            |                                                     | Datas deveriam ser DATE, preços e imposto deveriam ser FLOAT                           |
| Diagrama Lógico     | 9          |     | x   |            |                                                     | O nome da tabela não é levado em consideração ao identificar os atributos              |
| Diagrama Lógico     | 10         |     | x   |            |                                                     | CGC é o único atributo em caixa alta                                                   |
| Diagrama Lógico     | 11         | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 1          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 2          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 3          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 4          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 5          |     | x   |            |                                                     | Se baseia num diagrama lógico com tipos de variável já incorretos                      |
| Dicionário de Dados | 6          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 7          | x   |     |            |                                                     |                                                                                        |
| Dicionário de Dados | 8          |     | x   |            |                                                     | Se baseia num diagrama lógico já com falta de chaves primárias                         |
