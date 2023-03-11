# Atividades - Estrutura SE

1 - Verifique se o usuário digitou um valor igual a 10.

```javascript
programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número:\n")
    leia(numero)

    se(numero == 10){
      escreva("\nParabéns! Você digitou o número da sorte.")
    }
  }
}
```

2 - Crie um código para que o usuário digite um nome e senha e o sistema verifique se é correspondente a ( nome = admin e senha = 123)

```javascript
programa {
  funcao inicio() {
    cadeia nome
    cadeia senha

    escreva("Digite seu nome:\n")
    leia(nome)

    escreva("Digite sua senha:\n")
    leia(senha)

    se(nome == "admin" e senha == "123"){
      escreva("\nEscolha outro nome e senha!")
    }
  }
}
```

3 - Verifique se o usuário digitou o número 10 OU se digitou o número 5

```javascript
programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número:\n")
    leia(numero)

    se(numero == 10 ou numero == 5){
      escreva("\nParabéns! Você abriu o portal.")
    }
  }
}
```

4 - Verifique se o usuário digitou o número 10 E se digitou o número 5


5 - Solicite para o usuário digitar dois números, realize a soma e mostra se o resultado é maior que 50

```javascript
programa {
  funcao inicio() {
    inteiro numero1
    inteiro numero2

    escreva("Digite o primeiro número:\n")
    leia(numero1)

    escreva("Digite o segundo número:\n")
    leia(numero2)

    inteiro soma = numero1 + numero2

    se(soma > 50){
      escreva("\nParabéns! Você atingiu a nota suficiente.")
    }
  }
}
```
