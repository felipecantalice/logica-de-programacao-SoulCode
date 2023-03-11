# Atividades - Estrutura SENAO SE

1 -  Ler um valor e escrever se é positivo, negativo ou zero.

```javascript
programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite o número:\n")
    leia(numero)

    se(numero > 0){
      escreva("\nO valor é positivo!")
    } senao se(numero < 0) {
      escreva("\nO valor é negativo!")
    } senao {
      escreva("\nO valor é 0!")
    }
  }
}
```

2 - Ler dois valores e imprimir uma das três mensagens a seguir: 

‘Números iguais’, caso os números sejam iguais 
‘Primeiro é maior’, caso o primeiro seja maior que o segundo; 
‘Segundo maior’, caso o segundo seja maior que o primeiro.

```javascript
programa {
  funcao inicio() {
    inteiro n1
    inteiro n2

    escreva("Digite o primeiro número:\n")
    leia(n1)

    escreva("Digite o segundo número:\n")
    leia(n2)
 
    se(n1 > n2){
      escreva("\nPrimeiro é maior")
    } senao se(n1 < n2) {
      escreva("\nSegundo maior")
    } senao {
      escreva("\nNúmeros iguais")
    }
  }
}
```

3 -  Solicite ao usuário que informe um valor de 0 a 6. Logo após, o programa sorteia um valor também de 0 a 6 e exibe uma mensagem informando se o número sorteado e o número digitado são iguais.

```javascript
programa {
  funcao inicio() {
    inteiro n1
    
    escreva("Digite o número:\n")
    leia(n1)

    inteiro sorteio = u.sorteia(0,7)

    se(n1 == sorteio){
      escreva("\nVocê acertou o número! +1")
    } senao {
      escreva("\nDesculpe, não foi esse número que eu estava pensando!")
    }
  }
}
```

4 -  Ler 3 valores (considere que não serão informados valores iguais) e escrevê-los em ordem crescente.

```javascript
programa {
  funcao inicio() {
    
  }
}
```