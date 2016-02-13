---
layout: post
title: 'ERROR: Cookies are blocked or not supported by your browser'
date: 2015-03-18 11:53:11.000000000 -05:00
type: post
published: true
status: publish
categories:
- Learn
tags:
- cookies
- issue
- wordpress
meta:
  _publicize_pending: '1'
  geo_public: '0'
  publicize_google_plus_url: https://plus.google.com/+ClaudiaValdivieso/posts/BPj4pkMBg9U
  _wpas_done_6197447: '1'
  _publicize_done_external: a:1:{s:11:"google_plus";a:1:{s:21:"101114858139413196908";b:1;}}
  publicize_twitter_user: lavaldi_
  publicize_twitter_url: http://t.co/d0GkWNIwnO
  _wpas_done_4823758: '1'
  original_post_id: '31'
  _wp_old_slug: '31'
author:
  login: lavaldi
  email: claumavaldivieso@gmail.com
  display_name: lavaldi
  first_name: ''
  last_name: ''
---
<p>La semana pasada tuve este error en un blog de WordPress que estoy desarrollando, así que hago este post como una nota por si me vuelve a salir y puedo recurrir a mi propio blog.<!--more--></p>
<p>Pasos para depuración:</p>
<ol>
<li>Ve a la página de inicio de sesión (generalmente es así example.com/wp-login.php).</li>
<li>Presiona Ctrl + Shift + c (o da clic derecho y selecciona "Inspeccionar elemento") para abrir las herramientas de desarrolladores.</li>
<li>Introduce las credenciales en el formulario de login y pulsa Entrar. Luego obtendrás el error.</li>
<li>En el panel de herramientas de desarrollo ve al panel de Network.</li>
<li>En la pestaña de Network haz clic en el primer elemento (será wp-login.php) y selecciona la pestaña Headers y desplázate hasta el final.</li>
<li>Mira la(s) cabecera(s) Set Cookie, presta atención a <code>path=</code> y <code>domain=</code>.</li>
</ol>
<p><img class="aligncenter size-full wp-image-32" src="{{ site.baseurl }}/assets/wordpress-cookie-debug1.png" alt="ERROR: Cookies are blocked or not supported by your browser" width="878" height="452" /></p>
<p>Este error sucede cuando <code>wordpress_test_cookie</code> no es devuelto por el navegador, que, probablemente, es causada porque el dominio o el path son incorrectos.</p>
<p>En mi caso fue que, estábamos desarrollando un amigo y yo una web en localhost y al parecer WordPress se había quedado con las cookies del localhost de su PC y por eso Firefox y Chrome me mostraban dicho error.</p>
<p><strong>La solución</strong> es añadir:</p>
<pre>define('COOKIE_DOMAIN', false);</pre>
<p>al archivo wp-config.php. Al menos para mi ha funcionado, aunque he visto otras soluciones en la web.</p>
<p>P.D.: Una vez hecho esto, antes de actualizar tu página borra la caché del navegador y listo! ;)</p>
<p>&nbsp;</p>
