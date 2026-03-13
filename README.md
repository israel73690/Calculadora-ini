Algoritmo "CALCULADORA"

Var
   n1, n2, resultado: real
   opcao: inteiro


Inicio
   escreva("Digite o primeiro número: ")
   leia(n1)

   escreva("Digite o segundo número: ")
   leia(n2)

   escreval("Escolha a operação:")
   escreval("1- Soma")
   escreval("2- Subtração")
   escreval("3- Multiplicação")
   escreval("4- Divisão")
   
   leia(opcao)
   
   se opcao = 1 entao
   resultado <- n1 + n2
   escreval("Resultado: ", resultado)
   
   se opcao = 2 entao
   resultado <- n1 - n2
   escreval("Resultado: ", resultado)
   
   se opcao = 3 entao
   resultado <- n1 * n2
   escreval("Resultado: ", resultado)
   
   se opcao = 4 entao
   resultado <- n1 / n2
   escreval("Resultado: ", resultado)
   
   senao
   escreval("Opção Inválida")
   
fimse

Fimalgoritmo
