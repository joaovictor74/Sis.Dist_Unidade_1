# SISTEMAS DISTRIBUIDOS - CALCULADORA SIMPLES MULTITHREAD

  ## Sobre

  Uma calculadora que se conecta em 2 diferentes servidores:
  
  * ServerCalcA para operações básicas
    * Operações básicas:
        * ' + ' = Soma 
        * ' - ' = Subtração
        * ' / ' = Divisão
        * ' * ' = Multiplicação

  * ServerCalcB para operações especiais:   
    * Operações Especiais:
        * ' % ' = Porcentagem
        * ' ^ ' = Potência
        * ' # ' = Raiz
 
## Funcionamento
   * Regras:
        * Para qualquer uma das operações é necessário que inserção de dados esteja da seguinte forma : 
            * Operador1 Operando Operador2 
            * Obs: Os espaços são obrigatórios
            * EX: 10 + 10    
   * Só é possivel fazer uma operação por vez
    
  * Como funciona ?
    * O Operador1 e Operador2 são váriaveis que esperam um número do tipo real (Float)
    * O Operando é uma variavel que guarda o Operando inserido para fazer o calculo desejado, contanto que seja um dos operandos válidos este funcionará da seguinte forma:  
        * O operando ' + ' faz a Soma do "Operador1" com "Operador2"
        * O operando ' - ' faz a Subtração do "Operador1" com "Operador2"
        * O operando ' * ' faz a Multiplicação do "Operador1" com "Operador2"
        * O operando ' / ' faz a Divisão do "Operador1" com "Operador2"
        * O operando ' % ' faz o retorno do resto da divisão entre o "Operador1" com "Operador2"
        * O operando '  ^ ' faz o retorno da potência entre o "Operador1" (base) com "Operador2" (expoente)
        * O operando ' # ' faz a retorno da radiciação entre o "Operador1"(radicando) com "Operador2" (índice)

##  Endereçamento     
  * O endereço utilizado é "localhost" pode ser alterado na variavel "Ip"

## Portas
  * A porta ultilizada para o ServerCalcA é a "1000"
  * A porta ultilizada para o ServerCalcB é a "2000"
  * Obs:Ambas as portas podem ser alteradas pelas vaiaveis S e S2 respectivamente



