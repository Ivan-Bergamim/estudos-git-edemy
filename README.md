# Estudos de Git e GitHub

Este projeto tem por principio o estudo básico e desenvolvimento de habilidades com o Git e GitHub.

## Parte 1

O markdown se baseia no HTML.

A cerquilha (#) ou hashtag é utilizada para criar titulos ou topicos. Por exemplo, nos escritos "Estudso de Git e GitHub" e "Parte 1".

A hierarquia são os numeros de cerquilhas.

Abaixo tem-se um link para um guia basico de markdown:

https://www.markdownguide.org/getting-started/

## Parte 2

Escrevendo em itálico (pelos dois tipos possíveis):

_O rato roeu a roupa do rei de Roma._

Escrevendo em negrito (pelos dois tipos possíveis):

**O rato roeu a roupa do rei de Roma.**
__O rato roeu a roupa do rei de Roma.__

Links (três modos diferentes):

[Markdown Guide](https://www.markdownguide.org/getting-started/)

[Markdown Guide](https://www.markdownguide.org/getting-started/ "Site com infos de Markdown")

<https://www.markdownguide.org/getting-started/>

## Parte 3

Citação:

> Incluir a citação de alguém.
> Para quantas linhas você desejar.

Lista não ordenada:

- Frutas
    - Manga
    - Maçã
    - Pera
* Países
    * Brasil
    * Uruguai
    * Argentina
 
Lista ordenada:

1. Frutas
    1.1. Manga
    1.2. Maçã
    1.3. Pera
2. Países
    2.1. Brasil
    2.2. Uruguai
    2.3. Argentina

Lista ordenada automática:

1. Frutas
    1.1. Manga
    1.2. Maçã
    1.3. Pera
1. Países
    2.1. Brasil
    2.2. Uruguai
    2.3. Argentina
1. Linguagens de programação
    3.1. HTML
    3.2. Python
    3.3. Ruby

Imagens locais:

![Qualquer imagem](endereço local da imagem)

Imagem web:

![Qualquer imagem](https://p2.trrsf.com/image/fget/cf/1200/1200/middle/images.terra.com/2021/07/05/36-redsoc-geek-01-07-2021.png)

# Parte 4

Tabulação:

O alinhamento padrão é a esrquerda.

Produto|Preço
-------|------
PS5|R$ 4000,00
XBox Series X|R$ 3500,00
Nintendo Switch|R$ 2000,00

O alinhamento a direita.

Produto|Preço
-------:|------:
PS5|R$ 4000,00
XBox Series X|R$ 3500,00
Nintendo Switch|R$ 2000,00

O alinhamento ao centro.

Produto|Preço
:-------:|------
PS5|R$ 4000,00
XBox Series X|R$ 3500,00
Nintendo Switch|R$ 2000,00

Criação de um texto em uma linguagem de programação (sem coloração).

* Python
```
def soma(x, y):
    return x * y
```

* Javascript
```
function escrever_nome(nome){
    console.log(nome);
}
```

Criação de um texto em uma linguagem de programação (com coloração).

* Python
```python
def soma(x, y):
    return x * y
```

* Javascript
```js
function escrever_nome(nome){
    console.log(nome);
}
```

## Parte 5

Lista de tarefas

- [x] ~~Acordar~~
- [x] Levantar
- [ ] Café-da-manhã
- [ ] Escovar dentes

Separador de conteudo

---

Referência

[Site ESPN][espn]

[espn]: http://espn.uol.com.br/

O espn é a variavel que recebe o link a frente. Com isso podemos usar essa mesma variável em outros lugares do texto

## Criação do arquivo README.md

### Nome do projeto

> Resumo curto do que esse projeto faz ou é.

Um ou dois paragrafo sobre o projeto e o que ele faz.

Alocação de alguma imagem, ou logotipo, do seu projeto, que possa ser alto explicativo.

### Instalação do pacote/biblioteca/projeto

Instruções de como realizar a instalação, seja quais forem os sistemas operacionais disponíveis

```
pip install nome-projeto    
```


```
conda install nome-projeto    
```

### Algum tipo de exemplo

Alguns exemplos de uso, indicando como utilizado, assim o pra que serve na prática.

```python
import projeto

objeto = projeto.ALgumaClasse()

print(objeto)

```

Alguns prints da excecução e dividindo em tópicos pequenos para indicação de como se usa.

### Ambiente de desenvolvimento

DEscrição da instalação, assim como as dependencias do mesmo. Assim como indicação de cooperação para com outros usuarios, pois é um projeto open-source. Descrição de plataforma, assim como exemplos nestas plataformas.

## Historio de atualizações

* 0.2.3
    * Descrição desta versão e o diferencial com relação a outra.
* 0.2.2
    * Descrição desta versão e o diferencial com relação a outra.
* 0.2.1
    * Descrição desta versão e o diferencial com relação a outra.
    * É possivel colocar palavras chaves e códigos de muidança, alteração, consero etc.
    * FIX: concerto da função ``` exmeplo() ```.
* 0.0.1
    * Primeira versão

### Meta

Alguma referencia com os nomes dos contribuidores, como:
* Nome do autor principal
* Dos coloboradores
* Links com suas redes sociais
* Link de um site, se ele existir.
* Links para documentos de ajuda.
* Links de onde estão as tags

### Tipo de licença

Indicação da licença do projeto, pois como é algo publico, é necessário que exista alguma sewurança para com as informações colocadas aqui, indicando que você é o autor.
