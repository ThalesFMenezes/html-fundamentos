# Desafio 03 - Caminhos Relativos e Absolutos

## Objetivo

Compreender a diferença entre caminhos relativos e absolutos, aprendendo a localizar corretamente arquivos dentro de um projeto HTML.

## Perguntas

### 1. Explique com suas palavras a diferença entre caminho relativo e caminho absoluto.

**Resposta:**

- **Caminho relativo:** utiliza a localização do arquivo atual como ponto de partida para encontrar outro arquivo. Pode utilizar `../` para voltar pastas e navegar pela estrutura do projeto.

- **Caminho absoluto:** referencia um recurso a partir da raiz do projeto ou utilizando um endereço completo (URL), sem depender da localização do arquivo atual.

---

### 2. Qual deles é mais recomendado para projetos que serão enviados para outras pessoas?

**Resposta:**

O caminho relativo, pois funciona independentemente do computador onde o projeto estiver, desde que a estrutura das pastas seja mantida.

---

### 3. O que significa `../`?

**Resposta:**

Significa voltar uma pasta na estrutura de diretórios.

---

### 4. O que significa `./`?

**Resposta:**

Não lembrava durante a revisão.

**Após a correção:**

Representa a pasta atual. Em muitos casos pode até ser omitido.

---

### 5. O navegador consegue abrir o seguinte caminho?

```html
C:\Users\Thales\Desktop\logo.png
```

**Resposta:**

Não.

Esse caminho existe apenas no meu computador, portanto outros usuários ou servidores não conseguirão encontrar esse arquivo.

---

## Exercícios Práticos

### Exercício 1

Considere a estrutura:

```text
projeto/

│── index.html

├── imagens/
│   └── logo.png
```

Como o `index.html` acessa a imagem?

**Resposta:**

```html
<img src="imagens/logo.png">
```

---

### Exercício 2

Considere a estrutura:

```text
projeto/

├── paginas/
│   └── contato.html

├── imagens/
│   └── logo.png
```

Como o `contato.html` acessa a imagem?

**Resposta:**

```html
<img src="../imagens/logo.png">
```

---

### Exercício 3

Como um arquivo localizado dentro da pasta `css` acessaria a imagem `logo.png`?

**Resposta durante a prova:**

Não soube responder.

**Após a correção:**

```text
../imagens/logo.png
```

---

## Pergunta para reflexão

### Qual destes caminhos é absoluto?

```html
<img src="https://meusite.com/imagens/logo.png">
```

ou

```html
<img src="imagens/logo.png">
```

**Resposta:**

Durante a revisão fiquei em dúvida.

**Após a correção:**

O primeiro é um caminho absoluto, pois informa o endereço completo do recurso.

O segundo é um caminho relativo, pois depende da localização do arquivo HTML.

---

- Como localizar arquivos em diferentes diretórios.
- Por que não utilizar caminhos locais do computador.
- A importância de manter uma estrutura organizada de pastas em um projeto.
