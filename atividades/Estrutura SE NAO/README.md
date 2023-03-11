# Atividades - Estrutura SE NÃO

1 -  Leia um valor e informe ao usuário se o valor é maior ou igual a zero(0).

```javascript
programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número:\n")
    leia(numero)

    se(numero >= 0){
      escreva("\nO valor é maior ou igual a 0!")
    } senao{
      escreva("\nO valor é menor que 0!")
    }
  }
}
```

2 - Solicite ao usuário que informe a sua idade, voce deve criar um código que mostre se o usuario é maior ou menor de idade. considera-se (>=18 maior de idade)

```javascript
programa {
  funcao inicio() {
    inteiro idade

    escreva("Digite sua idade:\n")
    leia(idade)

    se(idade >= 18){
      escreva("\nVocê é maior de idade. Bem vindo!")
    } senao {
      escreva("\nVocê ainda é menor de idade. Não pode entrar!")
    }
  }
}
```

3 - Solicite para o usuário digitar dois números, realize a soma e mostra se o resultado é igual que 50, se o valor não for maior que 50 mostre a mensagem ( O resultado do calculo foi diferente de 50)

```javascript
programa {
  funcao inicio() {
    inteiro n1
    inteiro n2

    escreva("Digite o primeiro número:\n")
    leia(n1)

    escreva("Digite o segundo número:\n")
    leia(n2)

    inteiro soma = n1 + n2

    se(soma == 50){
      escreva("\nParabéns! Você ganhou um carro!")
    } senao {
      escreva("\nO resultado do calculo foi diferente de 50")
    }
  }
}
```

4 - Solicite ao usuário que informe três médias. Logo após, calcule  e exiba a média final destas notas. Por último, verifique se alguma das médias parciais é menor que a média final e a exibe (caso exista).

```javascript
programa {
  funcao inicio() {
    inteiro n1
    inteiro n2

    escreva("Digite o primeiro número:\n")
    leia(n1)

    escreva("Digite o segundo número:\n")
    leia(n2)

    inteiro soma = n1 + n2

    se(soma == 50){
      escreva("\nParabéns! Você ganhou um carro!")
    } senao {
      escreva("\nO resultado do calculo foi diferente de 50")
    }
  }
}
```