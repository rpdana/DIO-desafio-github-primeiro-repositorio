###JAVA

#### Conceituação de Variável

*" Um espaço na memória do computador onde se pode guardar valores."*

**Existem 4 tipos:**
- Instância: objeto.
- Classe: classe.
- Local: dentro dos métodos.
- Parâmetro: na assinatura do método.

**Padrão de definição:**

<*visibilidade*> <*modificador*> **tipo nome =**<*valor inicial*>;
- **tipo**, **nome** e **=** são obrigatórios para declarar uma variável.

**visibilidade** = "public", "protected" e "private"
**modificador** = "static" e "final"
**tipo** = tipo de dado
**nome** = nome dado a variável
**valor inicial** = um valor inicial, caso tenha.

**Convenções e regras:**

- Não devem começar com números.
- Embora permitido, "$" e "_" devem ser evitados.
- São case-sentivive.
- Sem espaços.
- Não pode usar palavras reservadas da linguagem.

***Boas práticas:***

- Sempre começar com letra minúscula.
- Nomes expressivos.
- Notação Camel.
- Quanto constante(final), maiúscula e separada por "_".


#### Conceituação de Tipos de Dados

*"São os valores e consequentemente operações  que as variáveis podem assumir e sofrer, respectivamente."*

**Tipificação**

- Estática(forte) VS Dinâmica (fraca).
- Primitivo VS Composto.

**Opções de tipos:**

- Textual: char.
- Numeral: int, long, float, double.
- Lógico: bool.
- Objeto: (String).

![valores](https://cdn.discordapp.com/attachments/836712599180935248/998704221702594640/Captura_de_tela_2022-07-14_173159.png)

***Boas práticas:***

- Usar adequadamente cada tipo de dado para cada informação.


#### Conceituação de Operadores Aritméticos

*"São simbolos especiais quais são capazes de realizar ações específicas em um, dois ou mais operandos e em seguida, retornar um resultado."*

**Tipos:**
- Pós-fixados: exp **++** ou exp **--**.
- Prefixados: **++** exp ou **--** exp.
- Aritmético: **+**, **-**, **/** e **%**.
- Atribuição: **=**, **+=**, **-=**, ***=**, **/=** e **%=**.

**Precedências:**

![precedencias](https://cdn.discordapp.com/attachments/836712599180935248/998704221371240529/Captura_de_tela_2022-07-14_171503.png)


#### Conceituação de Conversões(Casting):

*"É a transformação de uma determinada variável de tipo menos específico para um tipo mais específico ou vice-versa."*

**Tipos:**

- Upcasting (implícito)
- Downcasting (explícito)

**Casting**

![updown](https://cdn.discordapp.com/attachments/836712599180935248/998704221086035978/Captura_de_tela_2022-07-14_170340.png)

