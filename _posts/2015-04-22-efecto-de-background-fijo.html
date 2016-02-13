---
layout: post
title: Efecto de Background Fijo
date: 2015-04-22 18:09:45.000000000 -05:00
type: post
published: true
status: publish
categories:
- Learn
tags:
- background
- css
- fixed
- tutorial
meta:
  geo_public: '0'
  _publicize_pending: '1'
  publicize_facebook_url: https://facebook.com/429878900367225_915571711797939
  _wpas_done_3532641: '1'
  _publicize_done_external: a:1:{s:8:"facebook";a:1:{i:737475070;b:1;}}
  publicize_google_plus_url: https://plus.google.com/+ClaudiaValdivieso/posts/UVHKkvBfvhF
  _wpas_done_6197447: '1'
  publicize_twitter_user: lavaldi_
  publicize_twitter_url: http://t.co/0tSQe8xiHj
  _wpas_done_4823758: '1'
author:
  login: lavaldi
  email: claumavaldivieso@gmail.com
  display_name: lavaldi
  first_name: ''
  last_name: ''
---
<p><em>Artículo original en inglés <a href="http://codyhouse.co/gem/fixed-background-effect/">Fixed Background Effect</a> publicado en <a href="http://codyhouse.co/">CodyHouse</a></em></p>
<p><img class="aligncenter" src="{{ site.baseurl }}/assets/fixed-background-effect-featured-new.png" alt="" /></p>
<p>Aprovechamos la propiedad <code>background-attachment</code> de CSS para crear un efecto de fondo fijo.<!--more--></p>
<p style="text-align:center;"><a href="http://codyhouse.co/demo/fixed-background-effect/index.html" target="_blank">Demo</a> | <a href="http://codyhouse.co/redirect/?resource=fixed-background-effect" target="_blank">Descargar Código</a></p>
<p><strong>Soportado por:</strong></p>
<p><img class=" aligncenter" src="{{ site.baseurl }}/assets/8d5WpXI.png" alt="Navegadores soportados" /></p>
<p>A veces no es necesario código javascript a lo loco para tener efectos creativos y bonitos. Lo que vamos a ver hoy tiene que ver con una sola propiedad CSS: <code>background-attachment</code>. Se puede configurar el fondo fijo dentro de la ventana (<code>background-attachment: fixed;</code>).</p>
<p>El truco aquí es tener el mismo elemento (en este caso un teléfono) en la misma posición en todas las imágenes de fondo, por lo que mientras se hace scroll todo se mueve, menos el teléfono.</p>
<p>Los únicos assets que se necesitan son diferentes imágenes, con el mismo tamaño y un elemento común en la misma posición.</p>
<p><img class="aligncenter" src="{{ site.baseurl }}/assets/assets-needed.gif" alt="" /></p>
<h2>Creación de la estructura</h2>
<p>La estructura HTML es bastante básica: cada sección contiene un elemento <code>.content</code> con el título y párrafo. Clases <code>.img-1</code>, <code>.img-2</code> etc se utilizan para crear diferentes imágenes de fondo en CSS. El <code>.cd-vertical-nav</code> es la flecha de navegación (visible sólo en dispositivos grandes). Los <code>data-type</code> se han utilizado para identificar en jQuery las secciones/items del slider.</p>
<pre><code class="language-css">&lt;<span class="hljs-tag">section</span> <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-fixed-background</span> <span class="hljs-tag">img-1</span>" <span class="hljs-tag">data-type</span>="<span class="hljs-tag">slider-item</span>"&gt;
	&lt;<span class="hljs-tag">div</span> <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-content</span>"&gt;
		&lt;<span class="hljs-tag">h2</span>&gt;<span class="hljs-tag">Title</span> <span class="hljs-tag">here</span>&lt;/<span class="hljs-tag">h2</span>&gt;
		&lt;<span class="hljs-tag">p</span>&gt;<span class="hljs-tag">Lorem</span> <span class="hljs-tag">ipsum</span> <span class="hljs-tag">dolor</span> <span class="hljs-tag">sit</span> <span class="hljs-tag">amet</span>, <span class="hljs-tag">consectetur</span> <span class="hljs-tag">adipisicing</span> <span class="hljs-tag">elit</span>. <span class="hljs-tag">Autem</span> <span class="hljs-tag">dolor</span> <span class="hljs-tag">beatae</span>, <span class="hljs-tag">laudantium</span> <span class="hljs-tag">eos</span> <span class="hljs-tag">fugiat</span>, <span class="hljs-tag">deserunt</span> <span class="hljs-tag">delectus</span> <span class="hljs-tag">quibusdam</span> <span class="hljs-tag">quae</span> <span class="hljs-tag">placeat</span>, <span class="hljs-tag">tempora</span> <span class="hljs-tag">ea</span>? <span class="hljs-tag">Nulla</span> <span class="hljs-tag">ducimus</span>, <span class="hljs-tag">magnam</span> <span class="hljs-tag">sunt</span> <span class="hljs-tag">repellendus</span> <span class="hljs-tag">modi</span>, <span class="hljs-tag">ad</span> <span class="hljs-tag">ipsam</span> <span class="hljs-tag">est</span>.&lt;/<span class="hljs-tag">p</span>&gt;
	&lt;/<span class="hljs-tag">div</span>&gt;
&lt;/<span class="hljs-tag">section</span>&gt;

&lt;<span class="hljs-tag">section</span> <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-fixed-background</span> <span class="hljs-tag">img-2</span>" <span class="hljs-tag">data-type</span>="<span class="hljs-tag">slider-item</span>"&gt;
	&lt;!<span class="hljs-tag">--</span> ... <span class="hljs-tag">--</span>&gt;
&lt;/<span class="hljs-tag">section</span>&gt;

&lt;<span class="hljs-tag">nav</span>&gt;
	&lt;<span class="hljs-tag">ul</span> <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-vertical-nav</span>"&gt;
		&lt;<span class="hljs-tag">li</span>&gt;&lt;<span class="hljs-tag">a</span> <span class="hljs-tag">href</span>="<span class="hljs-id">#0</span>" <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-prev</span> <span class="hljs-tag">inactive</span>"&gt;<span class="hljs-tag">Next</span>&lt;/<span class="hljs-tag">a</span>&gt;&lt;/<span class="hljs-tag">li</span>&gt;
		&lt;<span class="hljs-tag">li</span>&gt;&lt;<span class="hljs-tag">a</span> <span class="hljs-tag">href</span>="<span class="hljs-id">#0</span>" <span class="hljs-tag">class</span>="<span class="hljs-tag">cd-next</span>"&gt;<span class="hljs-tag">Prev</span>&lt;/<span class="hljs-tag">a</span>&gt;&lt;/<span class="hljs-tag">li</span>&gt;
	&lt;/<span class="hljs-tag">ul</span>&gt; &lt;!<span class="hljs-tag">--</span> <span class="hljs-tag">cd-vertical-nav</span> <span class="hljs-tag">--</span>&gt;
&lt;/<span class="hljs-tag">nav</span>&gt;</code></pre>
<h2>Agregando estilo</h2>
<p>Un par de cosas importantes a tener en cuenta: los dispositivos iOS no les gusta <code>background-attachment: fixed;</code>, por lo tanto, <span style="text-decoration:underline;">en dispositivos pequeños el efecto de fondo fijo no será visible</span>. También en dispositivos pequeños que no usamos <code>background-images</code> todavía, pero inyectamos fotos pequeñas de los teléfonos como <code>::after</code> pseudo-elementos del elemento <code>.cd-content</code>.</p>
<pre><code class="language-css"><span class="hljs-class">.cd-fixed-background</span> <span class="hljs-class">.cd-content</span><span class="hljs-pseudo">::after</span> <span class="hljs-rules">{
	<span class="hljs-comment">/* phone image on small devices */</span>
	<span class="hljs-rule"><span class="hljs-attribute">content</span>:<span class="hljs-value"> <span class="hljs-string">''</span></span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">display</span>:<span class="hljs-value"> block</span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">width</span>:<span class="hljs-value"> <span class="hljs-number">100%</span></span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">padding</span>:<span class="hljs-value"> <span class="hljs-number">60%</span> <span class="hljs-number">0</span></span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">margin</span>:<span class="hljs-value"> <span class="hljs-number">2em</span> auto <span class="hljs-number">0</span></span></span>;
<span class="hljs-rule">}</span></span></code></pre>
<p>En segundo lugar, ya que estamos utilizando <code>background-images</code>, no podemos tener el 100% del control en donde aparecerá el elemento fijo (el teléfono en este caso). Esto es difícil de aceptar si estás obsesionado por la perfección de píxeles, pero no pude encontrar una solución para eso.</p>
<p>Este es todo el código que necesita para alcanzar el efecto de fondo fijo:</p>
<pre><code class="language-css"><span class="hljs-tag">html</span>, <span class="hljs-tag">body</span> <span class="hljs-rules">{
 	<span class="hljs-rule"><span class="hljs-attribute">height</span>:<span class="hljs-value"> <span class="hljs-number">100%</span></span></span>;
<span class="hljs-rule">}</span></span>

<span class="hljs-class">.cd-fixed-background</span> <span class="hljs-rules">{
	<span class="hljs-rule"><span class="hljs-attribute">height</span>:<span class="hljs-value"> <span class="hljs-number">100%</span></span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">background-repeat</span>:<span class="hljs-value"> no-repeat</span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">background-size</span>:<span class="hljs-value"> cover</span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">background-position</span>:<span class="hljs-value"> center center</span></span>;
	<span class="hljs-rule"><span class="hljs-attribute">background-attachment</span>:<span class="hljs-value"> fixed</span></span>;
<span class="hljs-rule">}</span></span>

<span class="hljs-class">.cd-fixed-background</span><span class="hljs-class">.img-1</span> <span class="hljs-rules">{
	<span class="hljs-rule"><span class="hljs-attribute">background-image</span>:<span class="hljs-value"> <span class="hljs-function">url</span>(<span class="hljs-string">"../img/img-1.jpg"</span>)</span></span>;
<span class="hljs-rule">}</span></span>

<span class="hljs-class">.cd-fixed-background</span><span class="hljs-class">.img-2</span> <span class="hljs-rules">{
	<span class="hljs-rule"><span class="hljs-attribute">background-image</span>:<span class="hljs-value"> <span class="hljs-function">url</span>(<span class="hljs-string">"../img/img-2.jpg"</span>)</span></span>;
<span class="hljs-rule">}</span></span>

<span class="hljs-class">.cd-fixed-background</span><span class="hljs-class">.img-3</span> <span class="hljs-rules">{
	<span class="hljs-rule"><span class="hljs-attribute">background-image</span>:<span class="hljs-value"> <span class="hljs-function">url</span>(<span class="hljs-string">"../img/img-3.jpg"</span>)</span></span>;
<span class="hljs-rule">}</span></span></code></pre>
<h2>Manejo de Eventos</h2>
<p>Utilizamos jQuery para implementar un slider básico para navegar por las diferentes secciones (Flechas anterior/siguiente y navegación del teclado). En la ventana de desplazamiento, actualizamos la visibilidad de las flechas (función <code>checkNavigation()</code>) y detectaremos la sección visible en la vista (la clase <code>.is-visible</code> se asigna utilizando la función <code>checkVisibleSection()</code>). Las funciones <code>nextSection()</code> y <code>prevSection()</code> se utilizan para navegar a la sección siguiente/anterior.</p>
<p style="text-align:center;"><a href="http://codyhouse.co/demo/fixed-background-effect/index.html" target="_blank">Demo</a> | <a href="http://codyhouse.co/redirect/?resource=fixed-background-effect" target="_blank">Descargar Código</a></p>
<hr />
<p><em>Artículo original en inglés <a href="http://codyhouse.co/gem/fixed-background-effect/">Fixed Background Effect</a> publicado en <a href="http://codyhouse.co/">CodyHouse</a></em></p>
