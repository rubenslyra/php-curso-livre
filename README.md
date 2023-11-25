# Aula 1: Introdução à Sintaxe Básica do PHP (Versões 7.2 a 8.2)

## Introdução

Nesta primeira aula do curso "PHP - O Videobook da Linguagem", vamos explorar a sintaxe básica do PHP nas versões 7.2 a 8.2. O PHP é uma linguagem de programação amplamente utilizada para desenvolvimento web, e entender sua sintaxe fundamental é o primeiro passo para se tornar um desenvolvedor PHP habilidoso. Vamos abordar os seguintes tópicos:

1. Sintaxe Básica do PHP
2. Tipos de Dados Suportados
3. Constantes e Variáveis (Introdução)

## 1. Sintaxe Básica do PHP

O PHP é uma linguagem de script incorporada em HTML. Isso significa que você pode mesclar código PHP diretamente em um arquivo HTML, tornando-o ideal para criar páginas web dinâmicas. Vamos começar com um exemplo simples:

```php
<!DOCTYPE html>
<html>
<head>
    <title>Minha Página PHP</title>
</head>
<body>
    <?php
    // Isso é um comentário em PHP
    echo "Olá, mundo!";
    ?>
</body>
</html>
```

Neste exemplo, usamos `<?php ... ?>` para incorporar código PHP em um documento HTML. O `echo` é usado para exibir "Olá, mundo!" na página.

## 2. Tipos de Dados Suportados

O PHP suporta diversos tipos de dados, incluindo:

- **Inteiro:** Números inteiros, como 42 e -10.
- **Flutuante:** Números com casas decimais, como 3.14.
- **String:** Sequências de caracteres, como "Hello, PHP!".
- **Booleano:** Valores verdadeiro (true) ou falso (false).
- **Array:** Coleções de valores associados a chaves.
- **Objeto:** Instâncias de classes.
- **Nulo:** Representa a ausência de valor.

Exemplo de uso de tipos de dados:

```php
$idade = 30; // Inteiro
$preco = 19.99; // Flutuante
$nome = "Maria"; // String
$ativo = true; // Booleano
$frutas = array("maçã", "banana", "laranja"); // Array
```

## 3. Constantes e Variáveis (Introdução)

Constantes são valores imutáveis no PHP, enquanto variáveis podem mudar de valor durante a execução do programa. Vamos criar uma constante e uma variável simples:

```php
define("PI", 3.14159); // Definindo uma constante chamada PI
$contador = 0; // Declarando e inicializando uma variável
```

Variáveis podem armazenar valores de diferentes tipos, e você pode alterar seus valores ao longo do programa.

```php
$nome = "João";
$idade = 25;

$nome = "Maria"; // Alterando o valor da variável $nome
$idade = $idade + 1; // Incrementando a idade em 1
```

## Conclusão

Nesta primeira aula, exploramos a sintaxe básica do PHP, os tipos de dados suportados e introduzimos constantes e variáveis. À medida que avançarmos no curso, aprofundaremos esses conceitos e exploraremos recursos mais avançados da linguagem PHP. 
