SmartLAMENT APP plugin (presentation marketing splash-scena)
============


**WARNING**

impress.js may not help you if you have nothing interesting to say ;)


HOW TO USE IT
---------------

[Use the source](http://e-parlament-gamesrol.c9.io/#/opciones), Gore_ ;)

If you have no idea what I mean by that, or you just clicked that link above and got 
very confused by all these strange characters that got displayed on your screen,
it's a sign, that smartLAMENT is not for you.

Sorry.

Fortunately there are some intriguing points, such as:
[https://titanpad.com/h4g-jsonrocks2]
8. Financiación
60% beneficio social / 40 % beneficio mercado

    Crowdfunding voluntaria. Por donaciones.
    Proyecto privado financiado con fondos públicos, 
    Recibir dinero público por investigación e innovación (incubadoras/aceleradoras)
    Ofrecer estadísitcas para las empresas o el instituto nacional de estadística.
    Servicio a colectivos o agrupaciones de colectivos, (asociaciones de vecinos, etc) identificamos que "propuestas de ley" necesitan esos colectivos para posibilitar sus objetivos.
    Uso por parte del público para generar aplicaciones
    Pasar auditoría de entidades superiores que te acreditan como entidadad certificadora de que esas ILP han pasado "el sello" de calidad tuyo.
    Comisiones promotoras, "somos tu comisión promotora", tramitamos tu Propuesta de ley.
    Venta directa a las administraciones públicas.
    Venta directa de la aplicación a medida a empresas que lo necesite.
    Publicidad.
    Mantenimiento de estadísticas y generación de nuevas propuestas. En plan Instituto de Estadística, te contratan el servicio de una estadística determinada. Unas estadísticas que cuentan con un conjunto "global" de muestreo.
    Ahorro que supone en cuanto personal o trabajo de campo hecho al tener un servidor corriendo con información sondeable, etc.

EXAMPLES AND OTHER LEARNING RESOURCES
---------------------------------------

### Official demo

[impress.js demo](http://bartaz.github.com/impress.js) by [@bartaz](http://twitter.com/bartaz)

### Examples and demos

More examples and demos can be found on [Examples and demos wiki page](http://github.com/bartaz/impress.js/wiki/Examples-and-demos).

Feel free to add your own example presentations (or websites) there.

### Other tutorials and learning resources

If you want to learn even more there is a [list of tutorials and other learning resources](https://github.com/bartaz/impress.js/wiki/impress.js-tutorials-and-other-learning-resources)
on the wiki, too.

There is also a book available about [Building impressive presentations with impress.js](http://www.packtpub.com/building-impressive-presentations-with-impressjs/book) by Rakhitha Nimesh Ratnayake.


WANT TO CONTRIBUTE?
---------------------

If you've found a bug or have a great idea for new feature let me know by [adding your suggestion]
(http://github.com/bartaz/impress.js/issues/new) to [issues list](https://github.com/aleph1888/impress.js).

If you have fixed a bug or implemented a feature that you'd like to share, send your pull request against [dev branch]
(http://github.com/JsonRock/smartlament/tree/dev). But remember that I only accept code that fits our vision of Smart CITY HIVE COLLECTIVE colaborative smarting inteligent.
and our coding standards - so make sure you are open for discussion :)



ABOUT THE NAME
----------------

VERSION HISTORY
-----------------

### 0.0.0 ([browse](http://e-parlament-gamesrol.c9.io), 

#### BUGFIX RELEASE



BROWSER SUPPORT
-----------------

### TL;DR;

Currently impress.js works fine in latest Chrome/Chromium browser, Safari 5.1 and Firefox 10.
With addition of some HTML5 polyfills (see below for details) it should work in Internet Explorer 10
(currently available as Developers Preview).
It doesn't work in Opera, as it doesn't support CSS 3D transforms.

As a presentation tool it was not developed with mobile browsers in mind, but some tablets are good
enough to run it, so it should work quite well on iPad (iOS 5, or iOS 4 with HTML5 polyfills) and 
Blackberry Playbook.

### Still interested? Read more...

Additionally for the animations to run smoothly it's required to have hardware
acceleration support in your browser. This depends on the browser, your operating
system and even kind of graphic hardware you have in your machine.

For browsers not supporting CSS3 3D transforms impress.js adds `impress-not-supported`
class on `#impress` element, so fallback styles can be applied to make all the content accessible.


### Even more explanation and technical stuff

Let's put this straight -- wide browser support was (and is) not on top of my priority list for
impress.js. It's built on top of fresh technologies that just start to appear in the browsers
and I'd like to rather look forward and develop for the future than being slowed down by the past.

But it's not "hard-coded" for any particular browser or engine. If any browser in future will
support features required to run impress.js, it will just begin to work there without changes in
the code.

From technical point of view all the positioning of presentation elements in 3D requires CSS 3D
transforms support. Transitions between presentation steps are based on CSS transitions.
So these two features are required by impress.js to display presentation correctly.

Unfortunately the support for CSS 3D transforms and transitions is not enough for animations to
run smoothly. If the browser doesn't support hardware acceleration or the graphic card is not 
good enough the transitions will be laggy.

Additionally the code of impress.js relies on APIs proposed in HTML5 specification, including
`classList` and `dataset` APIs. If they are not available in the browser, impress.js will not work.

Fortunately, as these are JavaScript APIs there are polyfill libraries that patch older browsers
with these APIs.

For example IE10 is said to support CSS 3D transforms and transitions, but it doesn't have `classList`
nor `dataset` APIs implemented at the moment. So including polyfill libraries *should* help IE10
with running impress.js.


### And few more details about mobile support

Mobile browsers are currently not supported. Even Android browsers that support CSS 3D transforms are
forced into fallback view at this point.

Fortunately some tablets seem to have good enough hardware support and browsers to handle it.
Currently impress.js presentations should work on iPad and Blackberry Playbook.

In theory iPhone should also be able to run it (as it runs the same software as iPad), but I haven't
found a good way to handle its small screen.

Also note that iOS supports `classList` and `dataset` APIs starting with version 5, so iOS 4.X and older
requires polyfills to work.


LICENSE
---------

Copyright 2011-2012 Bartek Szopka

Released under the MIT and GPL (version 2 or later) Licenses.


