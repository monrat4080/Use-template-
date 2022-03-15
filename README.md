# Use-template-
&lt;button onclick="showContent()">Show hidden content&lt;/button>  &lt;template>   &lt;h2>Flower&lt;/h2>   &lt;img src="img_white_flower.jpg" width="214" height="204"> &lt;/template>  &lt;script> function showContent() {   var temp = document.getElementsByTagName("template")[0];   var clon = temp.content.cloneNode(true);   document.body.appendChild(clon); } &lt;/script>
