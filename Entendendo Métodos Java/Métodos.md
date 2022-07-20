## Métodos

###Criação

**Conceituação**

*"É uma porção de código (sub-rotina) que é disponibilizada por uma classe. Este é executado quando é feita uma requisição a ele. São responsáveis por definir e realizar um determinado comportamento."*

#### Criação de métodos

**Padrão de definição:**

<*visibilidade*> <*tipo*> <*modificador*> **retorno nome** (<*parâmetros*>) <*exceções*> **corpo**

"<..>" = opicionais na criação de um método

**Visibilidade**: "public", "protected" ou "private" 
**Tipo**: concreto ou abstrato
**Modificador**: "static" ou "final"
**Retorno**: tipo de dado ou "void" // nao retorna nada só 
**Nome**: tipo de dado ou "void" // nao retorna nada só 
**Parâmetros**: parâmetros que pode receber // se o metodo for usado de ficar dentro do parametro ou parametro vazio
**Exceções**: exceções que pode lançar
**Corpo**: código que possui ou vazio


**Particularidades**

**Assinatura:** é a forma de identificar unicamente o método
 *Ass = nome + parâmetros(mesmo que seja uma lista vazia)*

**Construtor e Destrutor:** são métodos especiais usados na Orientação a Objetos. 

**Mensagem:** é o ato de solicitar ao método que o mesmo execute. Esta pode ser direcionada a um objeto ou a uma classe.

***Boas práticas***

- Nomes devem ser descritivos, mas curtos
- Notação camelo
- Deve possuir entre 80 e 120 linhas 
- Evite lista de parâmetros longas
- Visibilidades adequadas


### Sobrecarga

**Conceituação**

*"É a capacidade de definir métodos para diferentes contextos, mas preservando seu nome."*

#### Criação

**Alterar a assinatura do método:**
 *Ass = nome + parâmetros*

*Sobrecarga é Mudar a lista de parâmetros e manter o nome do método.*

**Exemplos:**

![sobrecarga](https://media.discordapp.net/attachments/836712599180935248/999129147018317854/unknown.png)


### Retorno

**Retorno** - É uma instrução de interrupção
Simbologia: *return*


#### Funcionamento

O método executa seu retorno quando:
- Completa todas suas instruções internas
- Chega a uma declaração explícita de retorno
- Lança uma exceção

#### Considerações

- O tipo de retorno do método é definido na sua criação e pode ser um tipo primitivo ou objeto;
- O tipo de dado do return deve ser compatível com o do método;
- Se o método for sem retorno(void), pode ou não ter um "return" para encerrar sua execução.

**Exemplos:**

![retorno](https://media.discordapp.net/attachments/836712599180935248/999133472679530526/unknown.png)


