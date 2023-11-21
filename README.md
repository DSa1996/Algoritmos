# Algoritmos
Exemplos de Algoritmos
programa {
  funcao inicio() {
    inteiro numero, i, multiplo
    escreva ("Introduza um número até 10 ")
    leia (numero)
    se ( numero < 0 ou numero > 10 )
    {
    escreva ("o número introduzido e invalido")
    }
    para (i=1; i<=10; i++)
    {
    multiplo = numero*i
    escreva (numero, "x", i, "=", multiplo, "\n" )
    }
  }
}
