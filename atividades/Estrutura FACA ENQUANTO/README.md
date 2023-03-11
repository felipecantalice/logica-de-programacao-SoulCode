# Atividades - Estrutura de Repetição FAÇA ENQUANTO

1 - Faça um programa que implemente um menu onde o usuário deverá selecionar 1 ou 0. Caso seja encontrado um número diferente, o programa deverá solicitar uma nova opção.

```javascript
programa {
  funcao inicio() {
  inteiro opcao = -1

  faca {
    escreva("Digite uma opção\n1 - Iniciar\n0 - Reiniciar:\n")
    leia(opcao)
  } enquanto(opcao != 1 e opcao != 0) 
  }
}
```

2 - Faça um programa que receba uma senha formada de quatro números inteiros, verifique se a senha está correta (senha correta = 1234) e, caso não esteja, solicite novamente a senha. Se a senha de entrada for correta, deverá ser apresentada a mensagem “Senha Correta”, caso contrário, “Senha Incorreta”.

```javascript
programa {
  funcao inicio() {

  logico valido = falso
  cadeia senha

  faca {
    escreva("Digite uma senha de 4 digitos:\n")
    leia(senha)

    se(senha == "1234"){
      valido = verdadeiro
      escreva("Senha correta!\n")
    } senao{
      escreva("Senha incorreta!\n")
    }

  } enquanto(valido == falso)   

  }
}

```