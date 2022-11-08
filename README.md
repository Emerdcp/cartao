# Cartão Virtual
> Projeto para trabalhar com HTML e CSS de forma inicial. O objetivo é criar um cartão virtual com informações de contato. Referencia: https://linktr.ee/

## Criando HTML
Todo arquivo html deve ter o nome com .html, exemplo:
index.html

> Sempre que tiver que iniciar um HMTL é colocar o "!" + Enter

> link:favicon ---> para colocar o icone na base da página, coloca sempre abaixo do title

### HTML - Hyper Text Markup Languege
### HTML ----> CONTEÚDO
```
<destacado>TEXTO</destacado>
<comando></comando>
<comando> --> <tag>
<p></p> --> parágrafo
<br> --> quabra linha
<img src-"foto.jpg"> --> imagem
<a href="https://sp.senac.br">Senac</a> --> link
<h1> ao <h6> ---> são usados para titulos
```
**Alt + Shif + F ---> Organiza automáticamente o código**

> CSS ---> ESTILO/FORMATAÇÃO
> JS --> INTERAÇÃO

## Criando o CSS
> CSS -> Cascadign Style Sheet (Folha de estilo em cascata). O CSS é modo pelo qual iremos formatar (estilizar) o nosso conteúdo (HTML).

Existem 3 formas de estilizar o conteúdo:

1. Inline - Formatação é feita diretamento no elemento HMTL.
```<img src="foto.jpg" style="width:150px">``` 
2. Na Página - Formantação é feita dentro de uma seção `<style>`.
```<style>
        .avatar{
            width: 150px;
        }
    </style>
```
3. **Arquivo Externo** - Criamos um arquivo exclusivo para formatação (.css).
```
 <link rel="stylesheet" href="estilo.css">
 ```
 > No href ao alter nome, pode ser dar um CTTOL + CLIQUE para ele criar o arquivo de CSS

A escolha do elemento HTML que será formatado, se dá atráves de seletores. Seletores são criados à partir de 3 possibilidade: tag, classe(.) e identificação (ID)

Por exemplo: imagine que queremos modificar o fundo so site para a cor laranja e a cor da letra para amarelo, podemos montar um seletor da seguinte forma:
```
body{
    background-color: orenge;
    color: yellow;
}
```
Explicação:

- body --> seletor (onde será formatado)
- backgraund-color --> propriedade (o que será formatado)
-  orange --> valor (como será formatado)

# Design: Estudo
 - tipogafia
 - cores
 - grid
 - espaçamento
 - gestalt
 - constrate

 
> Quando usaod rgba(91 ,10, 60, 0 ou 1) - é para colocar paravras com transparencia.

>control + ; faz comentario.