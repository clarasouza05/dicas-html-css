# dicas-html-css 
 ## ✨ Organizaçao para estudo em HTML e CSS ✨

link para estudo- Para clonagem de repositorio
https://www.alura.com.br/artigos/clonando-repositorio-git-github?gclid=EAIaIQobChMI9Onss5av_wIVczfUAR0W7waHEAAYASAAEgIcPvD_BwE

## HTML✨

PARA DEFINIÇAO DO HTML- É PRECISO USAR "<>" JUNTO COM A TAG.

° ``<html>``: Define o início e o fim do documento HTML.
° ``<head>:`` Contém informações sobre o documento, como título, metadados e referências a arquivos externos.
°``<body>:`` Envolve todo o conteúdo visível da página.
°``<h1>,`` ``<h2>,`` ``<h3>,```´<h4>,```´<h5>,`` `´<h6>`´: São títulos de diferentes níveis de importância.
°`´<p>:`´ Define um parágrafo de texto.
°``<a>:`` Cria um link para outra página ou recurso.
°``<img>``: Exibe uma imagem na página.
°`´<ul>,```´ <ol>,`´ `´<li>`´: Criam listas não ordenadas (com marcadores) e ordenadas (numeradas).
°``<div>,`` ``<span>``: São elementos de contêiner usados para agrupar outros elementos ou aplicar estilos específicos.
°O HTML É MERMITIDA A INCLUSAO DE ATRIBUTOS NAS SUAS TAGS.

## CSS✨

- UTLIZADA PARA DEFINIR APRENCIA E LAYOUT DE HTML, SENDO ASSIM UM COMPLEMENTO DO HTML.

- SENDO UTLIZADA ATRAVES DA TAG ``<style>`` SENDO ASSIM UMA PONTE ENTRE O HTML E CSS.

💢SELETOR= Usado para selecionar um ou mais elementos HTML que serão estilizados.

💢PROPRIEDADE= Define o aspecto específico que será alterado, como cor, tamanho da fonte, margem, entre outros.

💢VALOR= Especifica a configuração desejada para a propriedade, como uma cor específica, um tamanho de fonte em pixels, uma margem em pixels ou em porcentagem...

💢CASCATA= O CSS segue o princípio da cascata, onde várias regras podem ser aplicadas ao mesmo elemento, e a prioridade é determinada pela especificidade do seletor e pela ordem em que as regras são declaradas.

💢BOX MODEL= O CSS trata cada elemento HTML como uma caixa retangular com conteúdo, preenchimento, borda e margem. O box model define como essas propriedades afetam o layout e a aparência dos elementos.

💢RESPONSIVIDADE= O CSS permite criar layouts responsivos, adaptando a aparência de uma página para diferentes tamanhos de tela e dispositivos. 

💥💥💥(ALGUNS CODIGOS EM CSS)

💬 - Define a cor do texto para vermelho 

p {
  color: red;
}

	💬 - Define a fonte e o tamanho da fonte
h1 {
  font-family: Arial, sans-serif;
  font-size: 24px;
}

💬	- Adiciona sombra ao texto
h2 {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

💬	- Define uma cor de fundo e adiciona uma borda
div {
  background-color: #f2f2f2;
  border: 1px solid #ccc;
}

💬	- Define margens e preenchimento
p {
  margin-top: 10px;
  margin-bottom: 20px;
  padding: 5px;
}

💬- Alinha o texto ao centro dentro de uma caixa
h1 {
  text-align: center;
}


💬	- Remove a decoração de sublinhado dos links
a {
  text-decoration: none;
}

💬 - Altera a cor do link quando o cursor está sobre ele 
a:hover {
  color: red;
}

💬 - Define a cor de fundo, a cor do texto e o espaçamento interno do botão
button {
  background-color: #4CAF50;
  color: white;
  padding: 10px 20px;
}

💬 - Altera o estilo do cursor quando o cursor está sobre o botão
button:hover {
  cursor: pointer;
}

💬	- Adiciona uma transição suave ao passar o cursor sobre o botão
button {
  transition: background-color 0.3s ease;
}

💬 - Alterando a fonte e o tamanho da fonte
h1 {
  font-family: Arial, sans-serif;
  font-size: 24px;
}

💬 - Adicionando um fundo colorido
span {
  background-color: yellow;
}

💬 - Aplicando negrito e itálico
strong {
  font-weight: bold;
}

em {
  font-style: italic;
}



## Aula 06/06/2023- CSS✨

- Aprendendo como lincar html e css, mudança de cores.

- Com pesquisas, conseguir usar um codigo para marcar uma frase/texto (com o codigo   background-color).

- (Para o colocamente de novas caracteristas)
https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap
aprendemos como, mudar tamnho da fonte, colocar para varios lados, definir intencidade e escolher A FONTE.

- ALGUANS CODIGOS EM CSS APRENDIDOS EM SALA

.corAzul (para chama uma cor){
    color: rgb(236, 21, 21);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; /* para escolher a fonte do texto*/
font-weight: bold; /* para escolher a intencidade da fonte*/
font-size: 16px; /* para definir tamanho*/
text-align: end; /*para mover qualquer coisa para qualquer lado*/
}






  {color: #ce2828;
    border:1px solid #28bb65 ;
    display: flex ;
    box-sizing:border-box ;
    padding:10px ;
    margin:100px ;
    width:400px ;
    height: px;
    background-color:rgb(224, 152, 224);
  }
