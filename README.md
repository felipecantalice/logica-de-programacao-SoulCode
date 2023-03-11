# Curso de lógica de programação SoulCode

Curso voltado para adquirir os fundamentos da lógica, voltada para a computação. Entender uma maneira de criar soluções de forma coerentes para um computador, utilizando a linguagem Portugol para resolver as atividades.

## Fundamentos de programação

* Algoritmos
* Fluxograma
* Narrativa descritiva
* Pseudocodigo
* Portugol

## Conceitos básicos de programação

### Variáveis

Representam dados que podem ser manipulados durante a execução. Pode assumir vários valores durante a execução.

```javascript
inteiro idade = 19
real troco = 10.0

idade = 20
```

### Constantes

Representa um dado que podem ser adicionado durante a execução. Não pode assumir vários valores durante a execução.

```javascript
const inteiro idade = 19
const real troco = 10.0

idade =  // erro!
```

## Códigos

```javascript
// Tipos de dados
inteiro numero
real troco
caractere letra
cadeia frase
logico aprovado

// Valores constantes
const inteiro MAIOR_NOTA = 10
const real PI = 3.14

// Estrutura Condicional
logico expressao = 1 < 10

// se
se(expressao == verdadeiro){
    escreva("\nVerdade")
}

// senao
se(expressao == verdadeiro){
    escreva("\nVerdade")
} senao {
    escreva("\Falso")
}

// senao se
se(expressao == verdadeiro){
    escreva("\nVerdade")
} senao se(expressao == falso) {
    escreva("\nVerdade")
} senao {
    escreva("\Falso")
}

// escolha caso
inteiro opcao = 1
escolha(opcao){

    caso 1:
        escreva("Você é top!\n")
        pare
    caso 2:
        escreva("Você tem um nariz grande!\n")
        pare

    caso contrario:
        escreva("Opção inválida\n")
}

// Estrutura de repetição

// Para
para(inteiro numero = 1; numero <= 11; numero +=1){
    escreva("\n"+numero)
}

// enquanto ...
inteiro quantidade = 0

enquanto(quantidade <= 10){
    escreva("\n"+quantidade)
    quantidade = quantidade + 1
}

// faca ... enquanto ...
inteiro opcao = -1

faca {
    escreva("Digite uma opção\n1 - Iniciar\n0 - Reiniciar:\n")
    leia(opcao)
} enquanto(opcao != 1 e opcao != 0) 
```
