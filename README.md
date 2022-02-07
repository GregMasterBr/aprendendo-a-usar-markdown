# Aprendendo a usar markdown
Markdown Syntax é uma sintaxe usada para padronizar e facilitar formatação de texto na web, utilizada em aplicativos como Slack e [GitHub](#). 
Textos estilizados com Markdown são, na maioria dos casos, apenas texto com caracteres não-alfabéticos, como #, \* e ![](), usados para a configuração de títulos, listas, itálico, negrito e inserção de imagens. 
O Markdown funciona como um conversor de texto para HTML: os caracteres não-alfabéticos são traduzidos como &lt;b>, &lt;i> e &lt;a href>, etc. Já os textos sem formatação entram como parágrafo simples &lt;p>.


## **Hierarquia para titulação**
# Título <h1>
## Título <h2>
### Título <h3>
#### Título <h4>
##### Título <h5>
###### Título <h6>
  
 <br />

## Ênfase textual - Negrito e Itálico
**Negrito**: adicione dois asteriscos **texto** ou dois traços-baixos __texto__ no início e no fim do conteúdo.
*Itálico*: adicione apenas um asterisco *texto* ou um traço-baixo _texto_ no início e no fim do conteúdo.
  
## Links
Este é um [link em formato de texto](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open), e este é um link direto (https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open).  
  
  
## Criando listas ordenadas e não ordenadas
 
1. Item 1
2. Item 2
3. Item 3


* Item 1
* Item 2
* Item 3
  
<br />
  
## Usar imagem
![Gomu gomu no](https://alfabetajuega.com/hero/2020/03/one-piece-luffy-1.jpg?width=1200&aspect_ratio=1200:631)
  
## Citação

>Este é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
>código sinal.
  
## Código (Code Highlight)
  
Esta é uma linha que contém um `código`.

```
Esta é uma linha de código
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
  

## Tabela

Escolha os títulos das colunas e use | para delimitar as colunas. Depois, utilize hífen - na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o | para delimitar colunas. 

### Veja um exemplo abaixo:
  
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
  
  
Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize : ao lado do campo horizontal de hífens ---, na segunda linha da sua tabela. Veja abaixo:

* **Alinhado a esquerda**: usar : no lado esquerdo (alinhamento padrão);
* **Alinhado a direita**: usar : no lado direito;
* **Centralizado**: usar : dos dois lados.

 ### Veja no exemplo:  
 Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
