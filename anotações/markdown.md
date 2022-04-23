# Markdown

## **O que é Markdown?**  
![Alt ou título da imagem](/imagens/markdown.png)

Markdown é uma linguagem de marcação de texto.       


## **Marcações em Markdown:**    
### - **Titulação:**  

>
##### # Título 1 
##### ## Título 2
##### ### Título 3
##### #### Título 4
##### ##### Título 5
##### ###### Título 6
>

### **Como fica:**

# Título 1  
## Título 2  
### Título 3  
#### Título 4  
##### Título 5  
###### Título 6    

### - **Formatação:**

**Negrito:** 
` **negrito** ` ou ` __negrito__ `  
*Itálico*: ` *itálico* ` ou `_itálico_ `  
***Negrito e Itálico:*** ` ***negrito e itálico***`   
~~Riscado~~ : ` ~~riscado~~ `  
`Destaque:` ``` `destaque` ```  

### Links:  

>
Existem duas formas de inserir link em Markdown, através de um link direto ou usando um texto-âncora:
>
Com texto âncora
```
[Texto](www.google.com)
```
Ou apenas o link direto
```
<www.exemplo.com> 
```

Este é um `link em formato de texto`, e este é um link direto `https://site.com/`.   

## Imagens

O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação ! no início do código, como no exemplo abaixo:


```
![Alt ou título da imagem](URL da imagem)
```

Imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.
![cachorro feliz](/imagens/cachorro_feliz.jpeg)


Esta é uma linha com uma imagem personalizada .  

## Listas  

Para listas não ordenadas, utilize um asterisco * na frente do item da lista:
```
* Item 1
* Item 2
* Item 3
```
Fica assim:

* Item 1
* Item 2
* Item 3

Para listas ordenadas, utilize o número do item seguido de ponto . :

```
1. Item 1
2. Item 2
3. Item 3
```
Fica assim:

1. Item 1
2. Item 2
3. Item 3  

Em ambos os casos lembre-se de dar um espaço depois do ícone para o comando funcionar.  

## Citação (Quote)
```
Para transformar um texto em uma citação ou comentário, semelhante ao código HTML <blockquote>, utilize o sinal > no início da linha que será formatada:

```

```>Este é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
>código sinal. Isso gerará um novo parágrafo dentro do *blockquote*.
>Códigos de **negrito**, _itálico_ e <https://links.com> funcionam aqui.  
```  

### Como aparece no HTML:

Este é um blockquote. O sinal usado abre e fecha este código no HTML. Para adicionar mais uma linha à citação, basta teclar Enter para um novo código sinal. Isso gerará um novo parágrafo dentro do blockquote. Códigos de negrito, itálico e https://links.com funcionam aqui.  

## Bloco de código:  

Há dois modos de adicionar trechos de código ao Markdown:

- Código em linha (inline): adicione um acento crase ˋ no início e no final do código.  

- Múltiplas linhas de código: envolva as linhas de código com três acentos crases ˋˋˋ ou três tils ~~~.

 ```
 Esta é uma linha que contém um ˋcódigoˋ.


Esta é uma linha de código  
```

 Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o ˋˋˋ ou ~~~, por exemplo ~~~javascript ou ~~~ruby. Veja nos exemplos abaixo:  

```
 ~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~
```  

## Tabela
Escolha os títulos das colunas e use | para delimitar as colunas. Depois, utilize hífen - na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o | para delimitar colunas. Veja um exemplo abaixo:
```
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
```
Como aparece no Learning Center:

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8  

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize : ao lado do campo horizontal de hífens ---, na segunda linha da sua tabela. Veja abaixo:

Alinhado a esquerda: usar : no lado esquerdo (alinhamento padrão);
Alinhado a direita: usar : no lado direito;
Centralizado: usar : dos dois lados.  

Veja no exemplo:
```
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
```

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor

## Task lists

Basta você usar a notação - [ ] Texto da task (com um espaço dentro dos colchetes) para criar um checkbox desmarcado, ou então - [x] Texto da task, para um checkbox marcado. Exemplo:
```
- [ ] Comprar arroz
- [ ] Comprar feijão
- [ ] Comprar batata
- [x] Comprar macarrão
```

Como fica:

- [ ] Comprar arroz  
- [ ] Comprar feijão  
- [ ] Comprar batata  
- [x] Comprar macarrão  

## Conclusão

Anotações sobre os principais e mais utilizados recursos para quem deseja utilizar o Markdown sem neura. 

# Referências:

- [Pipz Academy](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
- [Sabrina Barros ](https://dev.to/sabrinabarros/o-que-e-markdown-e-como-ele-pode-melhorar-o-seu-readme-no-github-2n2l)
- [Raul Esteves](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)