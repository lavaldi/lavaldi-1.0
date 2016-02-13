---
layout: post
title: Seguridad Frontend en WordPress
date: 2015-03-25 16:35:48.000000000 -05:00
type: post
published: true
status: publish
categories:
- Learn
tags:
- escaping
- frontend
- php
- seguridad
- wordpress
meta:
  _publicize_pending: '1'
  geo_public: '0'
  publicize_google_plus_url: https://plus.google.com/+ClaudiaValdivieso/posts/TYaLY4AREJR
  _wpas_done_6197447: '1'
  _publicize_done_external: a:1:{s:11:"google_plus";a:1:{s:21:"101114858139413196908";b:1;}}
  publicize_twitter_user: lavaldi_
  publicize_twitter_url: http://t.co/M4XBn5Fthb
  _wpas_done_4823758: '1'
  original_post_id: '71'
  _wp_old_slug: '71'
author:
  login: lavaldi
  email: claumavaldivieso@gmail.com
  display_name: lavaldi
  first_name: ''
  last_name: ''
---
<p>Si desarrollas para WordPress es necesario que sepas lo básico de seguridad para desarrollar tu tema o plugin, especialmente ahora que se están dando tantos ataques a las páginas hechas con este CMS (a penas hace unos día me tocó resolver un problema de esos).<!--more--></p>
<h2>La seguridad es nuestra responsabilidad</h2>
<p>Pero</p>
<blockquote><p>"Si un hacker ya es capaz de cambiar el código/base de datos/contenido, ¿qué diferencia hace si mi código de front-end es seguro? ¿No podía ya hacer daño más importante?"</p></blockquote>
<p>Sí, es cierto,  si un hacker ya tiene el control del código o base de datos, lo más probable es que no les importa lo bien asegurado que esté el frontend (probablemente lo pueden cambiar de todos modos).</p>
<p>Aun así, todavía <strong>tienes la responsabilidad</strong> de hacer que el código frontend seguro. Aquí algunas razones:</p>
<ul>
<li>La seguridad frontal adecuada también <strong>evita que los errores de los usuarios causen grandes problemas.</strong> <span class="notranslate">Si el usuario pone accidentalmente un carácter especial en un campo donde se supone no tendría que estar, la página no va a explotar.&gt;</span></li>
<li><strong>Algunos ataques son limitados.</strong> Tal vez el hacker tuvo un control mínimo y sólo podía cambiar una sola pieza de contenido en la base de datos. <span class="notranslate">Puede evitar que el ataque sea mucho más grande.</span></li>
<li><strong>La seguridad es una cebolla.</strong> <span class="notranslate">La capa más externa (a menudo no comestible) es la parte frontal. Las buenas prácticas de seguridad hacen que sea un <em>poquito más difícil</em> para un hacker para explotar un sitio.</span></li>
</ul>
<h2>¿Qué nos preocupa?</h2>
<p>Nuestra preocupación como frontends es evitar los <strong>Cross-Site Scripting </strong>(XSS, porque "CSS" podría causar problemas :P ). Este tipo de vulnerabilidad permite que las personas ("hackers") puedan robar información. Normalmente significa robar coockies y la información de sesión.</p>
<h2>¿Qué es <em>Escaping</em>?</h2>
<p>En ciencias de la computación de la palabra "escape" tiene un significado especial:</p>
<blockquote><p>Convertir un carácter o cadena de caracteres a ser interpretados literalmente, dentro de un contexto específico, normalmente para evitar que esos caracteres sean interpretados como código.</p></blockquote>
<p>Dicho de otra manera, en el contexto del desarrollo frontend de WordPress: <em>Escaping</em> cambia el contenido <strong>posiblemente malo</strong> en contenido <strong>seguro.</strong></p>
<p>El mayor peligro es generalmente son las etiquetas <code>&lt;script&gt;</code> y otros métodos de ejecución de JavaScript (por ejemplo, <code>onclick="javascript:"</code> ). <span class="notranslate">Si un <code>&lt;script&gt;</code> se puede emitir en la página como ejecutable, es súper peligroso. <em>Escaping</em> significa tornarlo en &amp;lt;script&amp;gt; que es seguro.</span></p>
<h2>Un escape para todo</h2>
<p>Ahora, echemos un vistazo a los métodos de <em>Escaping</em> que ofrece WordPress.</p>
<h3>Función: esc_html (<a href="http://codex.wordpress.org/Function_Reference/esc_html" target="_blank">Codex</a>)</h3>
<p><strong>Utilizado para:</strong> No debe tener HTML en la salida.</p>
<p><strong>Lo que hace:</strong> Convierte los caracteres especiales HTML (como <code>&lt;</code> , <code>&gt;</code> , <code>&amp;</code> ) en su entidad "escaped" (<code>&amp;lt;</code> , <code>&amp;gt;</code> , <code>&amp;amp;</code> ).</p>
<p>Un ejemplo común sería mostrar en campos personalizados del tema sólo texto:</p>
<pre><code>&lt;?php $dog_name = get_post_meta( $post_id, 'dog_name', true ); ?&gt;
&lt;span class="dog-name"&gt;&lt;?php echo esc_html( $dog_name ); ?&gt;&lt;/span&gt;</code></pre>
<h3>Función: esc_attr (<a href="http://codex.wordpress.org/Function_Reference/esc_attr" target="_blank">Codex</a>)</h3>
<p><strong>Utilizado para:</strong> Se usa en el contexto de un atributo HTML ("title", campos "data-", el texto del "alt").</p>
<p><strong>Lo que hace:</strong> Es <em>exactamente</em> lo mismo que <code>esc_html</code> . <span class="notranslate">La única diferencia es que los diferentes filtros de WordPress se aplican a cada función.</span></p>
<p>Así es <code>esc_attr</code> utilizada en una imagen:</p>
<pre><code>&lt;img src="/images/duck.png"
alt="&lt;?php echo esc_attr( $alt_text ); ?&gt;"
title="&lt;?php echo esc_attr( $title ); ?&gt;" &gt;</code></pre>
<h3><span class="notranslate">Función: esc_url (<a href="http://codex.wordpress.org/Function_Reference/esc_url" target="_blank">Codex</a>)</span></h3>
<p><strong>Utilizado para:</strong> Bota <em>necesariamente</em> una URL. <span class="notranslate">Ejemplos de ello serían los atributos de imagen <strong>src </strong>y valores <strong>href.</strong></span></p>
<p><strong>Lo que hace:</strong> Elimina o convierte los caracteres no permitidos en las direcciones URL en URLs de formato seguro.</p>
<p>Utiliza <code>esc_url</code> cuando se necesita para generar un enlace o ruta dinámica de la imagen:</p>
<pre><code>&lt;a href="&lt;?php echo esc_url( $url ); ?&gt;"&gt;Link Text&lt;/a&gt;
&lt;img src="&lt;?php echo esc_url( $image_url ); ?&gt;" &gt;</code></pre>
<h3>Función: esc_js (<a href="http://codex.wordpress.org/Function_Reference/esc_js" target="_blank">Codex</a>)</h3>
<p><strong>Utilizado para:</strong> Imprimir cadenas JavaScript, principalmente en los atributos en línea como <code>onclick</code> .</p>
<p><strong>Lo que hace:</strong> Convierte caracteres especiales como <code>&lt;</code> , <code>&gt;</code> , quotes (cualquier cosa que podría romper el código JavaScript).</p>
<p><code>esc_js</code> es probablemente el menos utilizado de las funciones esc_, por varias razones:</p>
<ol>
<li><span class="notranslate">La mayoría JS se carga en un archivo separado.</span></li>
<li><span class="notranslate">La mayoría JS no se escribe en línea como atributos.</span></li>
<li><span class="notranslate">Para el JS <em>no-inline</em>, <code>json_encode</code> es una mejor opción.</span></li>
</ol>
<p><strong>Pero,</strong> si alguna vez se te tiene que "escapar" alguna línea JS, así es como lo harías:</p>
<pre><code>&lt;?php $message = get_post_meta( get_the_ID(), 'onclick_message', true ); ?&gt;
&lt;a href="/blog/" onclick="alert('&lt;?php echo esc_js( $message ); ?&gt;')"&gt;...&lt;/a&gt;</code></pre>
<h3>Función: json_encode (<a href="http://php.net/manual/en/function.json-encode.php" target="_blank">Referencia PHP</a>)</h3>
<p><strong>Utilizado para:</strong> Imprimir una variable de PHP para su uso en JavaScript.</p>
<p><strong>Lo que hace:</strong> Convierte una variable de PHP (objeto, string, array, lo que sea) en una representación JavaScript de esa variable PHP.</p>
<p>Útil en particular para bloques <code>&lt;script&gt;</code> que hacen uso de variables de WP. <span class="notranslate">Un ejemplo sencillo:</span></p>
<pre><code>&lt;?php $categories = get_categories(); ?&gt;
&lt;script type="text/javascript"&gt;
var allCategories = &lt;?php echo json_encode( $categories ); ?&gt;;
// Do something interesting with categories here
&lt;/script&gt;</code></pre>
<h3><span class="notranslate">Función: wp_kses (<a href="http://codex.wordpress.org/Function_Reference/wp_kses" target="_blank">Codex</a>)</span></h3>
<p><span class="notranslate"><strong>Utilizado para:</strong> La salida necesita permitir <em>algo</em> de HTML, pero no <em>todas las</em> etiquetas o atributos.</span></p>
<p><span class="notranslate"><strong>Lo que hace:</strong> Tiras del contenido de las etiquetas o atributos que no coinciden con la lista de las normas aprobadas.</span></p>
<p><span class="notranslate">Utiliza <code>wp_kses</code> si hay un contexto que permite que ciertas etiquetas (por ejemplo, etiquetas de formato en línea como <code>&lt;strong&gt;</code> y <code>&lt;em&gt;</code>) que se imprimirán como HTML.</span></p>
<p><span class="notranslate">Un ejemplo básico sería mostrar los comentarios:</span></p>
<pre><code>&lt;div class="comment-text"&gt;
&lt;?php
echo wp_kses(
$comment_text,
// Only allow &lt;a&gt;, &lt;strong&gt;, and &lt;em&gt; tags
array(
'a' =&gt; array(
// Here, we whitelist 'href' and 'title' attributes - nothing else allowed!
'href' =&gt; array(),
'title' =&gt; array()
),
'br' =&gt; array(),
'em' =&gt; array(),
'strong' =&gt; array()
)
);
?&gt;
&lt;/div&gt;</code></pre>
<h2>¿Qué pasa con <code>the_title</code> y <code>the_content</code> ?</h2>
<h4>1. WordPress hace el escaping automáticamente</h4>
<p>Funciones como <code>the_title</code> son funciones de conveniencia - herramientas que hacen el desarrollo de aplicaciones para el usuario más fácil. Por lo tanto, para que sea aún más fácil para los desarrolladores, WordPress ya hace el escaping automáticamente para <code>the_title</code>.</p>
<h4>2. Contexto: Algunos contenido es HTML</h4>
<p>En el caso de <code>the_content</code>, se espera que la salida sea HTML sin escaping. Cuando el usuario agrega un <code>&lt;div&gt;</code> a su contenido, podemos asumir que en realidad quieren un &lt;div&gt; como salida de la página - en lugar de la versión escaping.</p>
<p>Si tienes problemas de seguridad con un usuario que pueda agregar secuencias de comandos para la salida de <code>the_content</code>, puedes utilizar <code>wp_kses</code> para quitar las etiquetas no deseadas de la salida final. Esto sería útil en subdominios y alojamientos compartidos, y estoy bastante seguro de que esto es lo que utilizan en WordPress.com (donde a los usuarios no se nos permite añadir nuestro propio JavaScript :( ).</p>
<p>Consejo práctico: Si desea utilizar <code>the_title</code> como atributo HTML, utilice <a href="http://codex.wordpress.org/Function_Reference/the_title_attribute" target="_blank">the_title_attibute</a> para ahorrarse el escaping. <code>the_title_attribute</code> en acción:</p>
<pre><code>&lt;span title="&lt;?php the_title_attribute(); ?&gt;"&gt;...&lt;/span&gt;</code></pre>
<h2>Conclusión</h2>
<p>Hay muchos plugins y temas de WordPress que muestran el contenido sin <em>escaping</em> que resultan en vulnerabilidades XSS. Espero este artículo nos ayude a poner en práctica lo que ya está al alcance de nuestra mano y hacer nuestras cosas más seguras.</p>
<hr />
<p>Artículo original (en inglés): <a title="Introduction to WordPress Front End Security: Escaping the Things" href="https://css-tricks.com/introduction-to-wordpress-front-end-security-escaping-the-things/" target="_blank">Introduction to WordPress Front End Security: Escaping the Things</a> en <a href="https://css-tricks.com/" target="_blank">CSS-TRICKS</a></p>
<p>&nbsp;</p>
