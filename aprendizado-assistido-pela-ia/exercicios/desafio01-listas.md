# Desafio 01 - Listas

## Perguntas

### 1. Qual a diferença entre uma lista ordenada (`<ol>`) e uma lista não ordenada (`<ul>`)?

#### UL = LISTA NAO ORGANIZADA, ou seja, lista que nao tem ordem definida e sim pontos para separação, tendo opções para diferenciar como circle, square, disc, entre outros OL = LISTA ORGANIZADA, lista que possui opções de letras em maiusculo, minusculo, numeros e numeros romanos para criar ordem na lista

### 2. Qual a função da tag `<li>`?

#### li = ITEM DA LISTA, é a tag utilizada para criar os itens que estarao na ul ou ol

### 3. Quais valores podem ser utilizados no atributo `type` de uma lista ordenada (`<ol>`)?

#### a tag type é utilizada para especificar o que vai ser usado para listar os itens, seja A, a, I, i, 1

### 4. Cite pelo menos quatro tipos de marcadores para listas não ordenadas.

#### conheço somente esses 3 tipos: circle, square e disc, nao me recordo o quarto

### 5. Qual a diferença entre utilizar o atributo `type` em uma `<ol>` e utilizar `list-style-type` via CSS?

#### A, a, I, i e 1

### Desafio 1

Crie uma lista não ordenada contendo:

- HTML
- CSS
- JavaScript

Utilize o marcador `circle`.

<ul style="list-style-type:circle"> 
<li>HTML</li> 
<li>CSS</li>
<li>JavaScript</li> 
</ul>

### Desafio 2

Crie uma lista ordenada contendo:

- Introdução
- Desenvolvimento
- Conclusão

Utilize algarismos romanos maiúsculos.

<ol style="list-style-type:I">
<li>Introdução</li> 
<li>Desenvolvimento</li> 
<li>Conclusão</li> 
</ol>

### Desafio 3

Crie um menu de navegação utilizando uma lista não ordenada com os seguintes itens:

- Home
- Produtos
- Contato
- Login

Remova os marcadores da lista.

<ul style="list-style-type:none">
<li>HOME</li>
<li>PRODUTOS</li>
<li>Contato</li>
<li>Login</li> 
</ul>
