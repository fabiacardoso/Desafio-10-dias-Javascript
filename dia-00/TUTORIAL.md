# Dia 0: Olá, mundo!

## Noções básicas de JavaScript

### Estrutura Lexical

A estrutura lexical de uma linguagem de programação é o conjunto de regras elementares que informa como escrever programas nessa linguagem. É essencialmente a sintaxe de nível mais baixo de uma linguagem e especifica coisas como a aparência dos nomes de variáveis, os caracteres delimitadores para comentários e como uma instrução de programa é separada da próxima.

### Conjunto de caracteres

- Os programas JavaScript são escritos usando o conjunto de caracteres Unicode . Unicode é um superconjunto de ASCII e Latin-1 .
- JavaScript é uma linguagem que diferencia maiúsculas de minúsculas.
- JavaScript ignora os espaços que aparecem entre os tokens nos programas. Na maior parte do tempo, o JavaScript também ignora quebras de linha.

### Saída de impressão
Usamos o método console.log para gravar dados na saída padrão em JavaScript.

**EXEMPLO**
Execute o código abaixo para demonstrar a impressão com console.log .

function main() {
    console.log("You entered the following text in the Input box:");

    const input = readLine();
    console.log(input);
}

### Comentários
JavaScript oferece suporte a dois estilos de comentários, conforme demonstrado a seguir.

**Comentários Inline**
Qualquer texto entre a // e o final de uma linha é ignorado por JavaScript e tratado como um comentário:

```
console . log ( "Esta é uma instrução que não será ignorada." ); 
// Este é um comentário embutido e será ignorado
```

**Comentários em Bloco**
Qualquer texto entre /*e */também é tratado como um comentário:

```
console . log ( "Esta é uma instrução que não será ignorada." ); 
/ * 
* Este é um bloco de comentário e será ignorado 
* /
 
console . log ( "Esta é uma instrução que não será ignorada." );

/ * 
* Isso faz parte do nosso comentário de bloco e será ignorado 
* Isso faz parte do mesmo comentário de bloco e será ignorado 
* /
```

### Literais
Um literal é um valor de dados que aparece diretamente em um programa. Por exemplo:

```
// O número inteiro doze: 
12 

// O número de ponto flutuante um ponto dois: 
1.2 

// Uma string de texto: 
"Hello, World." 

// Outra string: 
'Hi!' 

// Um ​​valor booleano: 
verdadeiro 

// A ausência de um objeto: 
nulo 
```

Expressões mais complexas podem servir como literais de matriz e objeto.

```
// Um ​​inicializador de objeto: 
{ x :  1 ,  y :  2 } 

// Um ​​inicializador de matriz: 
[ 1 ,  2 ,  3 ,  4 ,  5 ] 
```

### Identificadores

Um identificador é simplesmente um nome que você pode especificar e usar como meio de se referir a um valor específico ou outro trecho de código. Em JavaScript, os identificadores são usados ​​para nomear variáveis ​​e funções, bem como para fornecer rótulos para certos loops de código.

Um identificador JavaScript deve começar com uma letra, um sublinhado ( _) ou um cifrão ( $). Os caracteres subsequentes podem ser letras, sublinhados, cifrões ou dígitos (ou seja, os números 0 a 9). Como muitas outras linguagens, o JavaScript não permite dígitos como o primeiro caractere de um identificador porque os torna mais facilmente distinguíveis dos números.

```
// Alguns identificadores válidos são: 
x 
variable_name 
sum13 
_variable 
$ variable
```

Vários identificadores são palavras ou palavras - chave reservadas , o que significa que fazem parte de um conjunto de palavras predefinidas que têm um significado especial no próprio idioma. Você não pode usar essas palavras como identificadores em seus programas. Por exemplo, for function são palavras reservadas em JavaScript. Além disso, há várias variáveis ​​e funções globais predefinidas; é importante evitar o uso desses nomes predefinidos para suas próprias variáveis ​​e funções.

### Ponto-e-vírgula Opcional

Como muitas linguagens de programação, JavaScript usa o ponto-e-vírgula ( ;) para separar as instruções umas das outras. Isso é importante porque torna o significado do seu código claro; sem um separador, o final de uma instrução pode parecer o início da próxima (e vice-versa). Em JavaScript, geralmente você pode omitir o ponto-e-vírgula entre duas instruções, desde que essas instruções sejam escritas em linhas separadas.