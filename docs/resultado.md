# Resultados

## Nível de Criticidade

![criticidade.png](https://uploaddeimagens.com.br/images/001/663/264/original/criticidade.png?1539197076)

**Referência**
> GALIN, Daniel. Software quality assurance: from theory to implementation. Pearson Education India, 2004.



| #  | Descrição do Defeito                                                              | Criticidade | Proposta de Reparo                                                                    | Prazo Sugerido p/ Reparos | Artefato            | 
|----|-----------------------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------|---------------------------|---------------------| 
| 1  | Nem Perfumaria nem Receita possuem identificador                                  | 4           | Adicionar um identificador à essas entidades                                          | 10 minutos                | DER                 | 
| 2  | Relacionamento entre Produto e Venda não possui indicador de fluxo                | 1           | Adicionar um idetificador de fluxo à essa relação                                     | 5 minutos                 | DER                 | 
| 3  | Um Produto não "comercializa" uma Venda ou o contrário                            | 1           | Modificar o nome da relação entre Produto e Venda                                     | 10 minutos                | DER                 | 
| 4  | O atributo "quantidade" se repete                                                 | 4           | Usar nomes mais significativos para a diferenciação                                   | 10 minutos                | DER                 | 
| 5  | "Nome" e "quantidade" não são nomes verdadeiramente significativos                | 2           | Usar nomes mais significativos para a diferenciação                                   | 10 minutos                | DER                 | 
| 6  | Não aborda todos os atributos de cliente                                          | 5           | Criar entidade Cliente contendo os atributos requisitados                             | 20 minutos                | DER                 | 
| 7  | A cardinalidade entre Medicamento e Receita difere nos dois diagramas             | 3           | Padronizar a cardinalidade nos diagramas                                              | 20 minutos                | Diagrama Lógico     | 
| 8  | Muitas entidades possuem apenas chaves secundárias                                | 4           | Adicionar um identificador à essas entidades                                          | 20 minutos                | Diagrama Lógico     | 
| 9  | Muitas cardinalidades sem sentido, como as da herança                             | 2           | Refatorar cardinalidades no diagrama                                                  | 30 minutos                | Diagrama Lógico     | 
| 10 | Alguns nomes de atributos/entidades estão em caixa alta e outros em caixa baixa   | 1           | Alterar todos os nomes de entidades para caixa alta e de atributos para caixa baixa   | 20 minutos                | Diagrama Lógico     | 
| 11 | O nome de tabela "comercializa" não é significativo                               | 2           | Renomear essa tabela de forma a especificar seu     escopo                            | 10 minutos                | Diagrama Lógico     | 
| 12 | Há nomes de atributos repetidos                                                   | 4           | Usar nomes mais significativos para a diferenciação                                   | 20 minutos                | Diagrama Lógico     | 
| 13 | Datas deveriam ser DATE, preços e imposto deveriam ser FLOAT                      | 4           | Utilizar tipos de dado adequados                                                      | 10 minutos                | Diagrama Lógico     | 
| 14 | Não aborda todos os atributos de cliente                                          | 5           | Criar entidade Cliente contendo os atributos requisitados                             | 30 minutos                | Diagrama Lógico     | 
| 15 | O nome da tabela não é levado em consideração ao identificar os atributos         | 2           | Padronizar os nomes de atributos para corresponder aos nomes de entidades             | 45 minutos                | Diagrama Lógico     | 
| 16 | Se baseia num diagrama lógico com tipos de variável já incorretos                 | 1           | Atualizar dicionário de dados com base na correção do erro do diagrama                | 10 minutos                | Dicionário de Dados | 
| 17 | Se baseia num diagrama lógico já com falta de chaves primárias                    | 1           | Atualizar dicionário de dados com base na correção do erro do diagrama                | 10 minutos                | Dicionário de Dados | 

**Tempo total gasto**: 4 horas e 40 minutos
