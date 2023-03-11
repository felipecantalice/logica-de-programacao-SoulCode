# Atividades - Estrutura ESCOLHA CASO

1 -  O programa deve solicitar ao usuário que escolha uma opção e exibe uma frase correspondente à opção escolhida.

1) Elogio

2) Ofensa

3) Sair


Em cada uma das opções coloque a mensagem (Você entrou em um menu)

```javascript
programa {
  funcao inicio() {
    inteiro opcao
    
    escreva("Digite uma opção:\n")
    escreva("1 - Elogiu\n")
    escreva("2 - Ofensa\n")
    escreva("3 - Sair\n")
    leia(opcao)

    escolha(opcao){

      caso 1:
        escreva("Você é top!\n")
        pare
      caso 2:
        escreva("Você tem um nariz grande!\n")
        pare
      caso 3:
        escreva("Cya!\n")
        pare
      caso contrario:
        escreva("Opção inválida\n")
      
    }
  }
}
```

2 - Crie um Menu para que o usuário tenha acesso a algumas opções no seu código

Soma
Solicite para o usuário digitar 2 número e ao final realize a soma e mostre o resultado na tela.
multiplicação
Solicite para o usuário digitar 2 número e ao final realize a multiplicação e mostre o resultado na tela.

Verificar Idade
Solicite para o usuário digitar seu nome e sua idade ao final o código deve mostrar se é maior de idade.

```javascript
programa {
  funcao inicio() {
    inteiro opcao
    
    escreva("Digite uma opção:\n")
    escreva("1 - Soma\n")
    escreva("2 - Multiplicação\n")
    escreva("3 - Verificar idade\n")
    leia(opcao)

    escolha(opcao){

      caso 1:
        
        inteiro n1
        inteiro n2

        escreva("Digite o primeiro número:\n")
        leia(n1)

        escreva("Digite o segundo número:\n")
        leia(n2)

        inteiro soma = n1 + n2
        escreva("Resultado: " + soma)

        pare
      caso 2:
        inteiro n1
        inteiro n2

        escreva("Digite o primeiro número:\n")
        leia(n1)

        escreva("Digite o segundo número:\n")
        leia(n2)

        inteiro soma = n1 * n2
        escreva("Resultado: " + soma)
        pare
      caso 3:

        cadeia nome
        inteiro idade
        
        escreva("Digite seu nome:\n")
        leia(nome)

        escreva("Digite sua idade:\n")
        leia(idade)

        se(idade >= 18){
          escreva("Bem vindo "+ nome +"! Você é maior de idade.")
        } senao {
          escreva("Desculpe "+ nome +". Você ainda é menor de idade.")
        }
        pare
      caso contrario:
        escreva("Opção inválida\n")
      
    }

  }
}
```

3 - Crie uma calculadora que solicite para o usuário dois números e realize:

Soma
Subtração
Multiplicação
Divisão

```javascript
programa {
  funcao inicio() {

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
        escreva("Opção inválida\n")
      
    }
  }
}
```