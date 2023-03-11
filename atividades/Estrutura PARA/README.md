# Atividades - Estrutura repetição PARA

1 -  Crie um programa que imprima 11 vezes a frase " Hello World!" utilizando uma estrutura sequencial e uma estrutura de repetição while.

```javascript
programa {
  funcao inicio() {
    cadeia frase = "Hello world!"
    para(inteiro numero = 1; numero <= 11; numero +=1){
      escreva("\n"+frase)
    }
  }
}
```

2 - Escrever um programa para exibir os números de 1 até 50 na tela.

```javascript
programa {
  funcao inicio() {
    para(inteiro numero = 1; numero <= 50; numero +=1){
      escreva("\nNúmero: "+numero)
    }
  }
}
```

3 - Fazer um programa para encontrar todos os números pares entre 1 e 100.

```javascript
programa {
  funcao inicio() {
    para(inteiro numero = 1; numero <= 100; numero +=1){
      se(numero % 2 == 0){
        escreva("\nNúmero: "+numero)
      }
    }
  }
}
```

4 - Ler um valor inteiro (aceitar somente valores entre 1 e 10) e escrever a tabuada de 1 a 10 do valor lido.

```javascript
programa {
  funcao inicio() {
    para(inteiro numero = 1; numero <= 100; numero +=1){
      se(numero % 2 == 1){
        escreva("\nNúmero: "+numero)
      }
    }
  }
}
```

5 - Fazer um programa para encontrar todos os números impar entre 1 e 100.

```javascript
programa {
  funcao inicio() {

    inteiro valor

    escreva("Tabuada digital\n")

    escreva("Digite o valor:\n")
    leia(valor)
    
    se(valor >= 1 e valor <= 10){
      escreva("Tabuada de "+ valor)
      para(inteiro numero = 1; numero <= 10; numero +=1){
        escreva("\n"+valor + " * " + numero + " = " + (numero * valor))
      }
        
    } senao{
      escreva("Valor inválido! Tente de 1 até 10\n")
    }
  }
}
```
