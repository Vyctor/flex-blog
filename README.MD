# Curso de Flexbox da Origamid

Nesse repositório se encontram os arquivos do curso de Flexbox da Origamid, que consiste em uma abordagem teórica sobre os fundamentos e propriedades e um projeto final, chamado Flex-Blog.

# Propriedades do Flex Container

 ```css
display: flex;
```
O elemento vira um flex-container e seus filhos se tornam um flex-item. 

```css
flex-direction: column;
```
Define a orientação dos flex-itens dentro do flex-container. Por padrão seu valor é **row**.

 ```css
flex-wrap: wrap;
```
Define se o elemento quebrará linha quando todos os flex-itens não couberem no flex-container. Por padrão seu valor é **no-wrap**. 

```css
flex-flow: row wrap;
```
É um atalho para as propriedades flex-direction e flex-wrap. Primeiro aceita a orientação, segundo se quebra ou não a linha.

```css
justify-content: ;
```
Alinha os itens em um container de acordo com a direçao. Só funciona se os itens não ocuparem todo o container.

```css
align-itens: ;
```
Alinha os itens em um container de acordo com o eixo do container. Só funciona se os itens não ocuparem todo o container. 

```css
align-content: ;
```
Alinha as linhas do container em relação ao eixo vertical. A propriedade só funciona se existir mais de uma linha de flex-itens.   

# Propriedades do Flex Item 

 ```css
flex-grow: ;
```
Define a habilidade de um flex-item de crescer. 

```css
flex-basis: ;
```
Indica o tamanho inicial do flex-item.

 ```css
flex-shrink: 1;
```
Define a capacidade de redução de tamanho do ítem.

 ```css
flex: 0 1 auto;
```
É um atalho para as propriedades flex-grow, flex-shrink e flex-basis. Geralmente você verá a propriedade flex nos flex-itens ao invés de cada um dos valores separados. 

 ```css
order: ;
```
Modifica a ordem dos flex itens. Sempre do menor para o maior, assim order: 1, aparece na frente de order: 5. 

```css
align-self: ;
```
Serve para defirnirmos o alinhamento específico de um único flex item dentro do nosso container. Caso um valor seja atribuído, ele passará por cima do que for atribuído no align-items do container.


# Projeto FlexBlog