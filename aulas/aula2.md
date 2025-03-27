## Framework

Conjunto de ferramentas, vamos admitir como bibliotecas e padrões de como usa-las.

## Framework vs Plataforma de Desenvolviento

Frameworks oferecem estrutura e ferramentas, mas dependem de outras tecnologias (como o React depende do navegador).
Plataformas, como o Flutter, fornecem tudo: linguagem, renderizador, bibliotecas e ferramentas integradas, permitindo criar apps completos de forma independente.

## Renderização no Flutter

Flutter não usa HTML e sim renderiza cada pixel na tela diretamente através do motor gráfico Skia que controlan totalmente o visual e comportamento da interface.
*Obs*: o React usa HTML e CSS renderizados pelo navegador.

## SDK (Software Development Kit)

Conjunto de ferramentas para compilar, testar e executar apps Flutter.

## Como que o Dart "vira Flutter"

O Dart é a linguagem de programação utilizada para escrever os apps Flutter. Mas o "Flutter" em si é o framework que interpreta e transforma esse código Dart em um aplicativo visual e funcional.

Quando você escreve código Dart com Flutter, ele é processado pelo **Flutter SDK**, que compila esse código para **código nativo** (no caso de Android/iOS). 

Durante esse processo:

- O código Dart define **como** o app deve se comportar e se parecer.
- A estrutura de widgets do Flutter traduz o código Dart em **elementos visuais interativos**.
- O **Skia** lê essas instruções e desenha **cada pixel** diretamente na tela.

## Lista de Exercícios em Dart (Lembrando da Lógica Básica)

1. Imprimir nome

2. Ler nome e imprimir

3. Adicionar o nome a uma lista

4. Exibir o número de elementos de uma lista

5. Imprimir todos os elementos de uma lista  
   a. Utilizando `for`.  
   b. Utilizando `for-in` (foreach).  
   c. Utilizando `while`.

6. Somar todos os elementos de uma lista de inteiros

7. Verificar se um número digitado está presente na lista

8. Contar quantos números pares existem em uma lista de inteiros

9. Criar uma nova lista com apenas os números maiores que 10

10. Verificar se todos os elementos da lista são positivos

11. Imprimir somente os nomes que começam com a letra "A"

12. Ler um número e imprimir se ele é maior, menor ou igual ao primeiro elemento da lista

