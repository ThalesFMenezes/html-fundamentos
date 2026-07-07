# Desafio 02 - Imagens

## Perguntas

### 1. Qual a função da tag `<img>`?

#### <img> é a tag utilizada para inserir fotos e gifs no site, <a> é a tag utilizada para inserir links e hyperlinks no site ou na imagem

### 2. O que faz o atributo `src`?

#### src significa de onde é a fonte do que quer ser inserido, ou seja, de onde vem, no caso se é algo baixado é utilizado o caminho do arquivo pra localizar, se é de um site, o link do site

### 3. Qual a importância do atributo `alt`?

#### alt é a alternativa caso a imagem nao seja gerada, um texto que descreva ou que explique por que nao carregou

### 4. O que acontece quando uma imagem não é encontrada?

#### se a imagem nao for encontrada, o texto utilizado no alt vai aparecer

### 5. Qual a diferença entre um caminho relativo e um caminho absoluto?

#### 

### 6. Qual destes caminhos é relativo?

```html
src="assets/logo.png"
```

ou

```html
src="https://site.com/assets/logo.png"
```

Explique sua resposta.

#### 

## 💻 Desafios Práticos

### Desafio 1

Insira uma imagem chamada:

```
cachorro.jpg
```

Ela deve possuir:

- texto alternativo;
- largura de 300 pixels.

#### <img src="cachorro.jpg" alt="Foto de um cachorro" width="300">

### Desafio 2

Transforme essa imagem em um link para o Google.

####

### Desafio 3

Imagine a seguinte estrutura:

```
projeto/

│── index.html

├── assets/
│   ├── logo.png
```

Como ficaria o atributo `src` para exibir a imagem?

#### <img src="assets/logo.png">

### Desafio 4

Agora imagine esta estrutura:

```
projeto/

├── paginas/
│   ├── contato.html

├── assets/
│   ├── logo.png
```

Como a página `contato.html` acessaria a imagem?

####

