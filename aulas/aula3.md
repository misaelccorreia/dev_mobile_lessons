### Tipagem

O Dart é fortemente tipado, ou seja uma vez atribuido um tipo a uma variável ela não muda.

### Exibindo uma variável no terminal $

```
print($varivel);
```

## Estruturas de Controle em Dart

### Condicionais

### `if / else`

```
if (x > 10) {
  print("Maior que 10");
} else {
  print("10 ou menor");
}
```

### `switch`

```
    switch (dia) {
  case "segunda":
    print("Começo da semana");
    break;
  default:
    print("Outro dia");
}
```

## Laços de Repetição

### `for`

```
for (int i = 0; i < 5; i++) {
  print(i);
}
```

### `while`

```
while (x < 5) {
  print(x);
  x++;
}
```

### `do...while`

```
do {
  print(x);
  x++;
} while (x < 5);
```

### `for-in`

```
for (var item in lista) {
  print(item);
}
```

### `forEach`

```
lista.forEach((item) => print(item));
```