# CSS - Cascading Style Sheets ![image](https://github.com/JesskaBasilio/aprendendo-CSS/assets/152433983/a7e9bb36-4ff7-4cdf-aa92-a5daa1322e17)

<p>O CSS (Cascading Style Sheets) é uma linguagem de estilo utilizada para controlar a apresentação visual de documentos HTML. Seu principal objetivo é separar a estrutura do conteúdo da sua aparência, permitindo uma maior flexibilidade e controle no design de páginas web. Ao aplicar estilos, cores, fontes e layouts, o CSS transforma simples documentos HTML em interfaces atraentes e funcionais.</p>

## Conteúdo Abordado nos Desafios

<p>Este repositório aborda os seguintes temas em CSS 👇<br><br>

Seletor | Declaração | Declaração
------- | ---------- | ----------
H1      | {color: blue;}| {font-size: 12px;}

Propriedade | Valor 
------- | ---------- |
color | blue |
font-size | 12px |


<div>
<h2><strong>🌟 Seletores</strong></h2>
<ul>

<li><b>📗 Seletor de Tags 📌 </b></li>

<p>Exemplo:</p>
<code>
p {<br>
  color: red;<br>
  text-align: center;<br>
}
</code>
<br><br>Nesse exemplo, todos os elementos da tag p (seletor) estarão alinhados no centro e em coloração vermelho. 
</p>

<li><b>📗 Seletor de ID 📌 </b></li>
<p>Exemplo:</p>
<code>
#color {<br>
  color: red;<br>
  text-align: center;<br>
}
</code>
<br><br>Nesse exemplo, todos os elementos da id = "color" (seletor) estarão alinhados no centro e em coloração vermelho.
</code>
</p>

<li><b>📗 Seletor de Classes 📌 </b></li>

<p>Exemplo:</p>
<code>
.color {<br>
  color: red;<br>
  text-align: center;<br>
}
</code>
<br><br>Nesse exemplo, todos os elementos da class = "color" (seletor) estarão alinhados no centro e em coloração vermelho.
</code>
</p>


<li><b>📗 Seletores Universais 📌</b></li>

<p>Exemplo:</p>
<code>
* {<br>
  color: red;<br>
  text-align: center;<br>
}
</code>
<br><br>Nesse exemplo, todos os elementos da da página html (seletor) estarão alinhados no centro e em coloração vermelho.
</code>

</p>


<li><b>📗 Seletores de Atributos 📌</b></li>

<p>Exemplo:</p>
<code>
[title] {<br>
  color: red;<br>
  
}
</code>
<br><br>Nesse exemplo, se houver mais de uma tag title todos os elementos da tag title (seletor) estarão em coloração vermelho. 
</p>
<p>Agora olhe esse exemplo:</p>
<code>
Netflix[title]{<br>
    color: red<br>
}
</code>
<br><br>Nesse exemplo, somente os elementos da tag title (seletor) com valor Netflix estarão em coloração vermelho. 
</p>

</ul>
</div>

<div>
<h2><strong>🌟 Combinadores</strong></h2>
<ul>

<li>📗Agrupamento de Seletores📌</li>
<br><p>Quando se quer declarar apenas um valor para muitos seletores, existe a possibilidade de declará-los em uma única linha. Exemplo: </p>
<p>Exemplo 1</p>
<code>
h1, h2 {<br>
    color:blue;
}
</code><br><br>
<p>Os textos do Título 1 e do Título 2 terão a cor azul. </p>
<p>Exemplo 2</p>
<code>
.drop, h1, #image {<br>
    background-color: black;
}
</code><br><br>
<p>Os elementos da classe drop, da ID image e o texto do Título 1 terão a cor de fundo preta. </p>
<li>Combinador de Descendente</li>
<li>Combinador Filho</li>
<li>Combinador Irmão</li>
</ul>
<br>

|Seletor|Exemplo|Descrição do exemplo|
|-------|-----------|----------------|
|#id	|#firstname	|Selects the element with id="firstname"|
|.class	|.intro	|Selects all elements with class="intro"|
|element.class|	p.intro|	Selects only < p > elements with class="intro"|
|*	|*	|Selects all elements|
|element|	p	|Selects all < p > elements|
|element,element,..|	div, p	|Selects all <div> elements and all < p > elements|
|||

</div>

<div>
<h3><strong>🌟 Propriedades de Dimensionamento e Espaçamento</strong></h3>
<ul>
<li>Largura e Altura</li>
<li>Largura e Altura Máxima e Mínima</li>
<li>Margin</li>
<li>Padding</li>
<li>Box Sizing</li>
</ul>
</div>

<div>
<h3><strong>🌟 Cores</strong></h3>
<ul>
<li>Cores Pré-definidas</li>
<p>Exemplo: red</p>
<li>RGB e RGBA</li>
<p>Exemplo: rgb(255, 99, 71) - Tomato | rgba(255, 99, 71, 0.5) - Tomato 50% transparente.</p>
<li>Hexadecimal</li>
<p>Exemplo: #ff6347 - Tomato</p>
<li>HSL e HSLA</li>
<p>Exemplo: hsl(9, 100%, 64%) - Tomato | hsla(9, 100%, 64%, 0.5) - Tomato 50% transparente.</p>
</ul>
</div>

<div>
<h3><strong>🌟 Imagens</strong></h3>
<ul>
<li>Propriedade Object-Fit</li>
<li>Propriedade Object-Position</li>
</ul>
</div>

<div>
<h3><strong>🌟 Fundo dos Elementos</strong></h3>
<ul>
<li>Alterando o Fundo dos Elementos</li>
<li>Redimensionando a Imagem de Fundo dos Elementos</li>
<li>Repetição das Imagens de Fundo</li>
<li>Posicionamento das Imagens de Fundo</li>
<li>Propriedade Background Attachment</li>
<li>Propriedade Background Origin</li>
<li>Propriedade Background Clip</li>
<li>Mesclagem</li>
<li>Propriedade Background</li>
</ul>
</div>

<div>
<h3><strong>🌟 Bordas</strong></h3>
<ul>
<li>Tamanho da Borda</li>
<li>Estilo da Borda</li>
<li>Cor da Borda</li>
<li>Propriedade Border</li>
<li>Arredondando os Cantos com a Propriedade Border Radious</li>
<li>Propriedade Border Image Source</li>
<li>Propriedade Border Image Slice</li>
<li>Propriedade Border Image Width</li>
<li>Propriedade Border Image Repeat</li>
<li>Propriedade Border Image Outset</li>
</ul>
</div>

<div>
<h3><strong>🌟 Fontes</strong></h3>
<ul>
<li>Onde Encontrar Fontes Personalizadas?</li>
<li>Personalizando as Fontes do Nosso Site</li>
<li>Aplicando Fontes Personalizadas com @Font-Face</li>
<li>Aplicando Fontes Personalizadas com @import url()</li>
<li>Alterando o Tamanho das Fontes com Font-Size</li>
<li>Estilo de Fontes (Font-Style)</li>
<li>Espessura das Fontes com Font-Weight</li>
<li>Variação das Fontes com Font-Variant</li>
<li>Propriedade Font-Stretch</li>
<li>Customizando a Altura da Linha com Line-Height</li>
<li>Propriedade Resumida Font</li>
</ul>
</div>





</p>
