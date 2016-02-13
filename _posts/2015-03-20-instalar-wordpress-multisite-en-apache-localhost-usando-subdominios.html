---
layout: post
title: Instalar Wordpress Multisite en Apache localhost usando subdominios
date: 2015-03-20 10:30:07.000000000 -05:00
type: post
published: true
status: publish
categories:
- Learn
tags:
- multisite
- subdominios
- tutorial
- wordpress
meta:
  _publicize_pending: '1'
  geo_public: '0'
  publicize_google_plus_url: https://plus.google.com/+ClaudiaValdivieso/posts/g9EYMMJUgaV
  _wpas_done_6197447: '1'
  _publicize_done_external: a:1:{s:11:"google_plus";a:1:{s:21:"101114858139413196908";b:1;}}
  publicize_twitter_user: lavaldi_
  publicize_twitter_url: http://t.co/1MWIJIQ8CY
  _wpas_done_4823758: '1'
  original_post_id: '41'
  _wp_old_slug: '41'
author:
  login: lavaldi
  email: claumavaldivieso@gmail.com
  display_name: lavaldi
  first_name: ''
  last_name: ''
---
<h2>Editar el host file</h2>
<p>En Windows este archivo se encuentra en la ruta <code>C:WindowsSystem32driversetc</code>, en Mac y Linux se encuentra en <code>/etc/hosts</code>. En Windows tienes que crear este archivo en algún otro lado y luego reemplazarlo ya que no te deja hacerlo directamente.<!--more--></p>
<p>Lo modificas de tal manera que quede algo así:</p>
<pre><code>127.0.0.1       example.com
127.0.0.1       site1.example.com
127.0.0.1       site2.example.com</code></pre>
<p>Cambia example.com por la ruta que desees.</p>
<h2>Editar archivo de configuración de Apache</h2>
<p>Buscamos el archivo <code>httpd-vhosts.conf</code> de XAMPP/LAMPP/MAMP. En Windows está en <code>C:xamppapacheconfextra</code>.</p>
<p>Checamos que la línea <code>NameVirtualHost *:80</code> esté en el archivo y sin comentar.</p>
<p>Luego pasamos a agregar el siguiente bloque de código:</p>
<pre><code>&lt;virtualhost *:80&gt;
	DocumentRoot "[RUTA DE TU INSTALACIÓN DE WORDPRESS]"
	ServerName example.com
	ServerAlias *.example.com
	&lt;directory "[RUTA DE TU INSTALACIÓN DE WORDPRESS]"&gt;
		AllowOverride All
		Options Indexes FollowSymLinks
		Order allow,deny
		Allow from all
	&lt;/directory&gt;
&lt;/virtualhost&gt;</code></pre>
<p>Cambia example.com por la ruta que desees.</p>
<p>Reiniciamos o iniciamos Apache y pasamos a la instalación de wordpress.</p>
<h2>Instalar Wordpress Multisite</h2>
<p><a title="Instalación de Wordpress" href="http://codex.wordpress.org/Installing_WordPress" target="_blank">Instalamos</a> <a title="Wordpress download" href="https://wordpress.org/download/" target="_blank">Wordpress</a> por el camino normal, luego en el archivos <code>wp-config.php</code>, después de:</p>
<pre><code>/* That's all, stop editing! Happy blogging. */</code></pre>
<p>colocamos la siguiente línea:</p>
<pre><code>define( 'WP_ALLOW_MULTISITE', true );</code></pre>
<p>Guardamos el archivo.</p>
<p>Ahora en vamos al menú <strong>Herramientas&gt;Configuración de la Red </strong>donde se te pedirá que elijas entre subdominios o subdirectorios para la instalación: en este caso elegiremos subdominios. Luego llenamos los datos y damos Instalar.</p>
<p><img class="aligncenter size-full wp-image-45" src="{{ site.baseurl }}/assets/crear-red-multisitio-wordpress.png" alt="crear-red-multisitio-wordpress" width="1008" height="440" /></p>
<p>A continuación, en esa misma pantalla, veremos una serie de códigos que debemos añadir manualmente a los archivos <code>wp-config.php</code> y <code>.htaccess</code> para <strong>terminar la activación de la red multisitio en WordPress.</strong></p>
<p>Guardas ambos archivos.</p>
<p>Y listo! Tu Wordpress Multisite está instalado :)</p>
<p>Ahora, cuando accedas de nuevo a la <strong>administración de tu nueva red WordPress</strong> descubrirás que hay varios cambios:</p>
<ul>
<li>Nuevo submenú en <strong>Inicio&gt;Mis sitios</strong> en los que estará la lista de sitios creados, en principio solo el principal. Desde esta pantalla puedes acceder a visitar cada sitio y su escritorio.</li>
<li>Nuevo menú en la barra de administración denominado <strong>Mis sitios</strong> desde el que acceder a las herramientas del Administrador de la red:
<ul>
<li>Escritorio de la red.</li>
<li>Sitios de la red, donde puede administrarlos, o sea, crearlos o incluso borrarlos.</li>
<li>Usuarios de la red, de todos los sitios.</li>
<li>Temas disponibles para la red, que puedes activar o desactivar para que estén disponibles en todos los sitios de la red.</li>
<li>Plugins disponibles para la red, que puedes activar o desactivar para toda la red.</li>
</ul>
</li>
<li>Ahora hay un nuevo tipo de usuario, el Super administrador o Administrador de la red. Puedes asignar a cualquier usuario la capacidad de administrar la red mediante una nueva casilla que aparece cuando lo editas.</li>
<li>En los <strong>Ajustes -&gt; Generales</strong> hay un nuevo ajuste donde establecer el idioma por defecto para la red, que debes cambiar nada más terminar la instalación a <em>Spanish;Castilian</em> pues nada más activar la red queda por defecto en Inglés.</li>
</ul>
<p><img class="aligncenter size-full wp-image-46" src="{{ site.baseurl }}/assets/nuevo-sitio-red-wordpress-multisitio1.png" alt="nuevo-sitio-red-wordpress-multisitio" width="1008" height="421" /></p>
<h3>Recursos:</h3>
<p><a title="WPMU DEV" href="http://premium.wpmudev.org/blog/ultimate-guide-multisite/" target="_blank">The Ultimate Guide to Wordpress Multisite</a></p>
