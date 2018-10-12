| ARTEFATO | ID QUESTÃO | SIM | NÃO | INDEFINIDO | OBSERVAÇÕES | DEFEITOS |
|:--------:|:----------:|:---:|:---:|:----------:|:-----------:|:--------:|
| DER | 1 || X ||| Modelo não considera que pode haver mais de um fabricante |
| DER | 2 || X ||| Nem Perfumaria nem Receita possuem identificador | 
| DER | 3 | X |||||
| DER | 4 | X |||||  
| DER | 5 || X ||| Relacionamento entre Produto e Venda não possui indicador |
| DER | 6 || X ||| Um Produto não "comercializa" uma Venda ou o contrário |
| DER | 7 ||| X | Não pode ser representado no DER ||
| DER | 8 | X |||||
| DER | 9 || X ||| O atributo "quantidade" se repete |
| DER | 10 || X ||| "Nome" e "quantidade" não são nomes verdadeiramente significativos |
| DER | 11 || X ||| De acordo com a notação Peter Chen, os atributos derivados devem ser representados por círculos tracejados |
| DER | 12 | X |||||
| DER | 13 | X |||||
| Diagrama Lógico | 1 | X |||||
| Diagrama Lógico | 2 || X ||| Muitas entidades possuem apenas chaves secundárias |
| Diagrama Lógico | 3 | X |||||
| Diagrama Lógico | 4 || X ||| Muitas cardinalidades sem sentido, como as da herança |
| Diagrama Lógico | 5 || X ||| Alguns estão em caixa alta e outros em caixa baixa |
| Diagrama Lógico | 6 | X |||||
| Diagrama Lógico | 7 | X |||||
| Diagrama Lógico | 8 || X ||| Datas deveriam ser DATE, preços e imposto deveriam ser FLOAT |
| Diagrama Lógico | 9 || X ||| O nome da tabela não é levado em consideração ao identificar os atributos |
| Diagrama Lógico | 10 || X ||| CGC é o único atributo em caixa alta (o cep, mesmo sendo também uma sigla, está todo em caixa baixa) |
| Diagrama Lógico | 11 | X |||||
| Dicionário de Dados | 1 | X |||||
| Dicionário de Dados | 2 | X |||||
| Dicionário de Dados | 3 || X ||| A descrição da entidade Receita deveria ser específica para a especialização "medicamento" |
| Dicionário de Dados | 4 | X |||||
| Dicionário de Dados | 5 || X ||| Se baseia num diagrama lógico com tipos de variável já incorretos |
| Dicionário de Dados | 6 | X |||||
| Dicionário de Dados | 7 | X |||||
| Dicionário de Dados | 8 || X ||| Se baseia num diagrama lógico já com falta de chaves primárias |
