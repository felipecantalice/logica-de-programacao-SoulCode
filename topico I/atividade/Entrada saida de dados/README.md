# Atividades - Entrada e Saída de dados

1 - Crie uma variável do tipo cadeia com o nome de nome e solicite para o usuário digitar o nome e você deve salvar na variável criada.

```javascript
programa {
  funcao inicio() {
     cadeia nome

    escreva("Digite seu nome:\n")
    leia(nome)
    escreva("Seu nome é ")
    escreva(nome)
  }
}
```

2 - Solicite para o usuário o nome e sua idade, após o usuário digitar esses valores você deve salvar em variáveis e ao final mostrar os dados para o usuário

```javascript
programa {
  funcao inicio() {
    cadeia nome
    inteiro idade

    escreva("Digite seu nome:\n")
    leia(nome)

    escreva("Digite sua idade:\n")
    leia(idade)

    escreva("Seu nome é ")
    escreva(nome)

    escreva(" e sua idade é ")
    escreva(idade)
  }
}
```

3 -  Solicite que o usuário informe a sua data de nascimento em Mês, Dia e Ano, salve em variáveis do tipo necessário e ao final mostre para o usuário o resultado da execução do código

```javascript
programa {
  funcao inicio() {
    inteiro dia
    inteiro mes
    inteiro ano

    escreva("Digite o dia em que você nasceu:\n")
    leia(dia)

    escreva("Digite o mês em que você nasceu:\n")
    leia(mes)

    escreva("Digite o ano em que você nasceu:\n")
    leia(ano)

    escreva("Você nasceu no dia " + dia + " no mês " + mes + " no ano " + ano + ".")
  }
}
```

4 - Solicite ao usuário o valor de 2 numeros, após realize o calculo de soma e multiplicação dos números digitados e mostre o resultado na tela

```javascript
programa {
  funcao inicio() {
    inteiro n1
    inteiro n2

    escreva("Digite o primeiro número:\n")
    leia(n1)

    escreva("Digite o segundo número:\n")
    leia(n2)

    escreva("O resultado da soma é:")
    escreva(n1 + n2)

    escreva("\nO resultado da multiplicação é:")
    escreva(n1 * n2)
  }
}
```

5 - Crie um código que solicite ao usuário a sua idade (em anos) e você deve mostrar quantos dias de vida ele ja viveu (Considere que todos os anos tenham 365)

```javascript
programa {
  funcao inicio() {
    inteiro idade
    const inteiro dias_do_ano = 365

    escreva("Digite sua idade em anos:\n")
    leia(idade)

    escreva("Você já viveu: ")
    escreva(idade * dias_do_ano)
    escreva(" dias")
  }
}
```