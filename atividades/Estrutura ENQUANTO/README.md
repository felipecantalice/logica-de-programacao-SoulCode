# Atividades - Estrutura de Repetição ENQUANTO

1 - Crie um programa que imprima 11 vezes a frase " Hello World!" utilizando uma estrutura sequencial e uma estrutura de repetição enquanto.

```javascript
programa {
  funcao inicio() {
    cadeia frase = "Hello World!\n"
    inteiro quantidade = 0

    enquanto(quantidade <= 10){
      escreva(frase)
      quantidade = quantidade + 1
    }
  }
}
```

2- Escreva um algoritmo que leia um número do teclado até que encontre um número menor ou igual a 1.

```javascript
programa {
  funcao inicio() {
    inteiro numero = 2

    enquanto(numero > 1){
       escreva("Digite um número:\n")
       leia(numero)
    }

    escreva("Ufa! Você saiu do loop.")
  }
}
```

3 - Crie uma calculadora que solicite para o usuário dois números e realize:

Soma

Subtração

Multiplicação

Divisão

O programa deve solicitar o menu até que o usuário digite o número 0

```javascript
programa {
  funcao inicio() {

    logico menu = verdadeiro

    enquanto(menu == verdadeiro){

      escreva("\nBem vindo a calculadora:\n\n")

      inteiro n1
      inteiro n2

      escreva("Digite o primeiro número:\n")
      leia(n1)

      escreva("Digite o segundo número:\n")
      leia(n2)

      inteiro opcao
      
      escreva("Digite uma opção:\n")
      escreva("1 - Soma\n")
      escreva("2 - Subtração\n")
      escreva("3 - Multiplicação\n")
      escreva("4 - Divisão\n")

      leia(opcao)

      escolha(opcao){

        caso 1:
          escreva("Resultado: "+ (n1 + n2))
          pare
        caso 2:
          escreva("Resultado: "+ (n1 - n2))
          pare
        caso 3:
          escreva("Resultado: "+ (n1 * n2))
          pare
        caso 4:
          escreva("Resultado: "+ (n1 / n2))
          pare
        caso contrario:
          menu = falso
        
      }
    }
  }
}
```

4 - Solicite ao usuário que informe 10 números. Logo após, calcula e  exibe a média dos números digitados. 

```javascript
programa {
  funcao inicio() {
    inteiro quantidade = 1
    inteiro total = 0

    enquanto(quantidade <= 10){

      inteiro n1

      escreva("Digite o "+ quantidade +"° número:\n")
      leia(n1)

      total = total + n1
      quantidade = quantidade + 1
    }

    escreva("Resultado: "+ (total / 10))
  }
}
```