# HTML5

HiperText Markup Language (HTML), é uma ferramenta criada em 1991 com o intuito construir a estrutura do conteúdo e organizar as informações de um website, tendo textos, imagens, vídeos, gifs, entre outros.

| Linguagem | Ano  |
|:---------:|:----:|
| HTML1     | 1991 |
| HTML2     | 1995 |
| HTML3     | 1997 |
| HTML4     | 1997 |
| HTML5     | 2014 |

### Elementos

Um website pode conter várias páginas em html, e cada uma delas será composta por uma série de elementos, ou também chamados de tags. 

\- E afinal, o que são tags? 

Tags são códigos que definem toda a estrutura da página, como o seu tamanho, fonte, cores, as quebras de linhas, e muito mais. Grande parte das tags possuem uma abertura e um fechamento, por exemplo: `<tag> </tag>`. No entanto, há algumas tags de estrutura única, como a tag `<br/>`, que é utilizada para quebrar linha.

#### Exemplos de tags

- `<html>` - é a raiz do documento, todos os elementos devem estar dentro dela;

- `<head>` - local para declarar todas informações, como título e metadados;

- `<body>` - local para declarar todos os elementos que irão compor o corpo da página;

- `<h1>`-`<h6>` - tags para definir um título e subtítulos, indo de 1 a 6;

- `<p>` - tag para definir um parágrafo;

- `<a>` - tag de link, junto ao atribut o *`href=""`* é reponsável pela principal característica da web;

- `<header>` - define um cabeçalho;

- `<section>` - define uma seção;

- `<article>` - define um artigo;

- `<div>` - define uma divisão;

- `<footer>` - define um rodapé;

- `<nav>` - define uma área de navegação;

- `<table>` - define uma tabela;

- `<ol>` - define uma lista ordenada;

- `<ul>` - define uma lista não ordenada;

- `<li>` - deine um item de uma lista;

- `<form>` - define um formulário;

- `<input>` - define os campos do formulário;

- `<textarea>` - define uma área para o usuário digitar um texto;

- `<button>` - define um botão;

- `<img>` - permite inserir uma imagem ao documento.

#### Estrutura Básica

```html
<!DOCTYPE html> <!-- Tipo do Documento -->
<html lang="pt-BR"> <!-- Abertura do html e atribuição da lingua que será exibida na página -->
<head> <!-- Abertura do head -->
    <meta charset="UTF-8"> <!-- Tipos de caracteres -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css"> <!-- Referência onde será puxado o código de estilo em CSS -->
    <title>Document</title> <!-- Título que será exibido na aba -->
</head> <!-- Fechamento do head -->
<body> <!-- Abertura do body -->

</body> <!-- Fechamento do body -->
</html> <!-- Fechamento do html -->
```

#### Códigos na Prática

##### Semântica

```html
<!-- Abertura e Fechamento de tags que oraganizam melhor o código -->
<body>
    <header>

    </header>
    <section>
        <article>

        </article>
    </section>
    <footer>

    </footer>
</body>

<!-- Obs.:
    Pode parecer meio confuso por não ter nenhum conteúdo dentro das tags, mas isso é apenas uma demonstração da estrutura, que aliás, servem exatamenta para o que se refere seus nomes.
    <header> → cabeçalho
    <section> → seção
    <footer> → rodapé
    <article> → artigo (esse tem uma relevância maior em uma página, pois pode servir como um post de um blog. Um article pode conter outros elementos, como header, p, img)
-->
```

##### Textos e Links

```html
<!-- Parágrafo -->
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero rerum quis eligendi neque nam quae saepe, repudiandae nihil corporis modi, natus dolorem pariatur eaque! Temporibus suscipit voluptatibus voluptates magni accusantium.</p>

<!-- Links -->
<a href="https://web.dio.me" target="_blank">DIO</a>

<a href="mailto:lucas@gmail.com">e-mail</a>

<!-- Obs.:
    href → redireciona o usuário para outra página através de um hiperlink.
    target → redireciona o usuário para outra página, porém em uma nova aba do navegaodr.
    "mailto:" → 
-->
```

##### Imagens

```html
<!-- Imagens em arquivo local -->
<img src="imagem/avatar-pfp.png" alt="Foto de Perfil">

<!-- Imagens vindas da web -->
<img src="https://canaltech.com.br/empresa/google/" alt="Logo da Google">

<!-- Obs.:
    src="" → é o caminho no qual será usado para pegar a imagem.
    alt="" → é utilizado para acessibilidade e quando a imagem não carrega, para isso é descrito o que a imagem apresenta.
-->
```

##### Listas

```html
<!-- Lista Ordenada -->
<ol>
    <li>Maçã</li>
    <li>Manga</li>
    <li>Mexirica</li>
</ol>

<!-- Lista Não Ordenada -->
<ul>
    <li><a href="https://cursoemvideo.com" target="_blank">Curso em Vídeo</a></li>
    <li><a href="https://grasshopper.app" target="_blank">Grasshopper</a></li>
    <li><a href="https://web.dio.me" target="_blank">DIO</a></li>
</ul>
```
