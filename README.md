<h1 style="text-align: center;"> Desafio Pegadas</h1>


<h2>0. Sumário</h2>
<ol>
	<li><a href="#intro">Introdução</a></li>
	<li><a href="#anima">Animações</a></li>
	<li><a href="#difi">Principais desafios</a></li>
	<li><a href="#ref">Referencias</a></li>

</ol>
<h2 id="intro">1. Introdução:</h2>
<p> 	Para o desafio utilizei o framework Bootstrap que já vinha sendo usado no template base, para as animações utilizei uma biblioteca de css, <a style="color: red;" href="https://daneden.github.io/animate.css/">Animate</a>, não utilizei o vue.js pois não entendi bem como ele funciona, talvez por não ter bases em javascript antes, comecei a estudar a documentação do js para depois estudar a documentação do vue.js, porém eu tive uma impressão que esse framework é mais utilizado como um "gatilho" das animações do que para as animar os elemetos.</p>
<h2 id="anima">2. Animações:</h2>
<h3>Animação dos icones:</h3>
<table style="text-align: center;">
	<tr>
		<th >//</th>
		<th>Giz de cera</th>
		<th>Lápiz</th>
		<th>Tubo de ensaio</th>
		<th>Globo</th>
		<th>Molécula</th>
		<th>Livro</th>
		<th>Logo pegada</th>
	</tr>
	<tr>
		<th>Animação</th>
		<td>heartBeat</td>
		<td>bounce</td>
		<td>flipInY</td>
		<td>flipInX</td>
		<td>bounceIn</td>
		<td>rotateIn</td>
		<td>Jello</td>			
	</tr>
</table>
<p> Os icones acima foram animados para mesmo sendo objetos inanimados as crianças atribuirem vida ao objeto e com esse surreal dispertar o interesse da criança no portal.</p>
<h3>Animação dos personagens:</h3>
<table style="text-align: center;">
	<tr>
		<th></th>
		<th>Garota</th>
		<th>Garoto</th>
	</tr>
	<tr>
		<th>Animação</th>
		<td>bounceInRight</td>
		<td>bounceInLeft</td>
	</tr>
</table>
<p>
	Os personagens foram animados de forma que chamassem atenção para a area de login, principal area da pagina.
</p>
<h2 id="difi">3. Principais desafios:</h2>
<p>
	<ol>
		<li>Background do formulario de login</li>
		<li>"Esqueceu sua senha?" fora do background de login</li>
		<li>Animação para os personagens.</li>
	</ol>
<h3>Background do formulario de login:</h3>
<p> Ao inicio do projeto estava com dificuldade em colocar um background no formulario de login, como solução troquei o form por uma div.</p>
</p>
<h3>"Esqueceu sua senha?" fora do background de login:</h3>
<p> Em seguida outro problema persistia, se o "Esqueceu sua senha?" ficasse dentro da div acabaria não seguindo o design original onde esse elemento fica fora do quadrado de login, se ficasse fora ele estaria desalinhado, como solução coloquei para esse elemento se localizar 95% depois do ponto inicial da div.</p>
<h3>Animação para os personagens:</h3>
<p> Inicialmente a animação escolhida para os personagens seria a animação bounce, onde eles ficariam pulando, porémm além de ser algo enjoativo tiraria a atenção da area mais importante, o login, então para chamar a atenção para o login fiz a animação em direção dessa area.</p>
<h2 id="ref">4. Referencias:</h2>
<ul>
	<h3>Documentação:</h3>
	<li><a href="https://github.com/daneden/animate.css">Animate</a></li>
	<li><a href="https://getbootstrap.com.br/">Bootstrap</a></li>
	<li><a href="https://br.vuejs.org/v2/guide/index.html">Vue.Js</a></li>
	<h3>Artigos:</h3>
	<li><a href="http://pdf.blucher.com.br.s3-sa-east-1.amazonaws.com/designproceedings/ped2016/0201.pdf">RECOMENDAÇÕES PARA DESENVOLVIMENTO DE INTERFACE PARA ESTIMULAÇÃO DAS INTELIGÊNCIAS MÚLTIPLAS EM CRIANÇAS DE 3 A 5 ANOS</a></li>
	<h3>Links:</h3>
	<li><a href="https://webinsider.com.br/usabilidade-em-interfaces-para-criancas/">Usabilidade em interfaces para crianças</a></li>
</ul>
