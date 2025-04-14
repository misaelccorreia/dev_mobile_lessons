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