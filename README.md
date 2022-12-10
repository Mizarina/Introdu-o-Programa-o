# Introdu-o-Programa-o
Calculadora Simples
algoritmo "Calculadora"
// Função :       Calcular
// Autor :         Gabriela
// Data : 09/12/2022
// Seção de Declarações 
var

resultado : real
numero : real
operacao : caractere
continuar : caractere
inicio
// Seção de Comandos 
escreval ("----- CALCULADORA -----")

escreval (" ")

repita

escreval ("Digite o primeiro número: ")
leia (resultado)

escreval ("Escolha a operação [+ - * /]")
leia (operacao)

escreval ("Digite o número: ")
leia (numero)

escolha operacao

caso "+"
resultado <- resultado+numero

caso "-"
resultado <- resultado-numero

caso "*"
resultado <- resultado*numero

caso "/"
resultado <- resultado/numero

fimescolha

escreval(" ")

escreval ("O seu número é: ")
escreval (resultado)

escreva ("Deseja continuar S/N")
leia (continuar)

se (continuar = "s") entao

limpatela

senao
fimse

ate (continuar = "n")

fimalgoritmo
