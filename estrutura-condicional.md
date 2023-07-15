## Estruturas de controle condicional 

As estruturas condicionais no JavaScript permitem controlar o fluxo de execução do código com base em condições específicas. Elas permitem que você tome decisões e execute diferentes blocos de código com base em determinadas situações. Aqui estão as principais estruturas condicionais em JavaScript:

    • if: A estrutura if é usada para executar um bloco de código se uma condição for avaliada como verdadeira. Se a condição for verdadeira, o bloco de código dentro das chaves {} é executado. Caso contrário, o bloco é ignorado.
        ◦ if (condicao) { // código a ser executado se a condição for verdadeira }
      
    • else: A estrutura else é usada em conjunto com if para especificar um bloco de código a ser executado quando a condição do if for avaliada como falsa. O bloco de código dentro das chaves {} do else é executado se a condição do if for falsa.
        mediaReal = 7
        mediaJoao = 6.5
        
        ◦ if () {
            // código a ser executado se a condição for verdadeira
          }
        
        ◦ if (mediaJoao >= mediaReal) {
            "João passou"
          } else {
            "João reprovado"
          }
      
    • else if: A estrutura elseif é usada quando há necessidade de verificar múltiplas condições. Ela é utilizada entre um if e um else e permite especificar uma nova condição a ser avaliada. Se a condição do if for falsa, a condição do elseif será avaliada e, se for verdadeira, o bloco de código correspondente será executado.
        
        ◦ if (condicao1) {
            // código a ser executado se a condição1 for verdadeira
        } else if (condicao2) {
            // código a ser executado se a condição1 for falsa e a condição2 for verdadeira
        } else {
            // código a ser executado se nenhuma das condições anteriores for verdadeira
        }

Essas estruturas condicionais permitem que você tome decisões com base em diferentes condições e execute blocos de código apropriados em cada caso. Elas são fundamentais para controlar o fluxo do programa e executar ações condicionais em JavaScript.

É importante notar que as estruturas else e elseif são opcionais. Você pode usar apenas o if se não houver necessidade de um bloco alternativo. Além disso, você pode aninhar estruturas if, else e elseif para criar lógica condicional mais complexa.

As estruturas de controle condicional if, else e elseif são fundamentais para a tomada de decisões em programas JavaScript, permitindo que você execute diferentes blocos de código com base em diferentes condições.

O switch é uma estrutura condicional que permite testar uma expressão em relação a uma série de casos e executar um bloco de código correspondente ao caso que corresponder à expressão.
switch (expressao) {
  case valor1:
    // código a ser executado se a expressao for igual a valor1
    break;
  case valor2:
    // código a ser executado se a expressao for igual a valor2
    break;
  case valor3:
    // código a ser executado se a expressao for igual a valor3
    break;
  default:
    // código a ser executado se nenhum caso corresponder à expressao
    break;
}
No exemplo acima, a expressao é testada em relação a diferentes valorX. Se a expressao for igual a um dos valorX, o bloco de código correspondente a esse caso será executado. O comando break é usado para sair do switch após executar o bloco de código correspondente. Se nenhum caso corresponder à expressão, o bloco de código dentro do default será executado.

O switch é útil quando você precisa testar uma expressão em relação a vários casos possíveis e executar diferentes ações com base no resultado. Ele oferece uma alternativa ao uso de várias instruções if e else if, especialmente quando há muitos casos a serem considerados.
