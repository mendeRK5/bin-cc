Validação para cartão de crédito.
====================

Bin e padrões para validação de cartão de crédito.


Os dados dos cartões: Elo, Hipercard desta tabela *não* são oficiais.
Tentei diversas vezes falar com o pessoal dessas bandeiras afim de ter uma informação oficial, porém, é muito difícil falar com o setor técnico e as atendentes nem sabem o que é bin de cartão :(

Esta tabela inicialmente foi montada com coleta de dados de cartões de crédito reais. Onde o usuário colocava o número do cartão de crédito dele e quando não conseguíamos saber qual a banheira pedíamos para que o usuário selecionasse a bandeira e desta forma armazenavamos os primeiros digitos do cartão.

### Pull Request, contribua

Fique a vontade para mandar um PR para que esta tabela permaneça atualizada. Ao fazer o PR por favor, informe como conseguiu essa informação de atualização para que possamos sempre ter dados confiáveis nesta tabela.


| Bandeira   | Começa com                                  | Máximo de número | Máximo de número cvc |
| ---------- | ------------------------------------------- | ---------------- | -------------------- |
| Visa       | 4                                           | 13,16            | 3                    |
| Mastercard | 5                                           | 16               | 3                    |
| Diners     | 301,305,36,38 [link](http://bin-iin.com/American-Express-BIN-List.html)                               | 14,16            | 3                    |
| Elo        | 636368, 636369, 438935, 504175, 451416, 636297,5067,4576,4011,506699 | 16               | 3                    |
| Amex       | 34,37                                       | 15               | 4                    |
| Discover   | 6011,622,64,65                              | 16               | 4                    |
| Aura       | 50                                          | 16               | 3                    |
| jcb        | 35                                          | 16               | 3                    |
| Hipercard  | 38,60                                       | 13,16,19         | 3                    |
