# Repositorio de Haxe

**Mantenido por:** Ciro Duran <ciro.duran@gmail.com>

## Objetivo de este Repositorio

Este repositorio tiene como objetivo ser una introducción al lenguaje de
programación Haxe, y las librerías con las que está escrito. En segundo
lugar es un repositorio que contiene código y librerías interesantes producidas
por los mantenedores.

## Sobre Haxe

[Haxe](http://haxe.org/) es un lenguaje de programación de alto nivel, que
produce código para diferentes plataformas con un solo código base. Haxe
actualmente es capaz de compilar su código a ActionScript 3, Javascript
(incluyendo node.js), Java, C#, C++, Python, PHP y Lua. Así, el lenguaje ofrece
la capacidad de hacer aplicaciones isomórficas: aplicaciones que emplean el
mismo lenguaje para el cliente y el servidor.

El lenguaje en sí es muy similar a Javascript, con la ventaja añadida de tener
un sistema fuerte de tipos (que incluye especificación de funciones), con un
compilador que es capaz de deducir los tipos.

El lenguaje también cuenta con
un sofisticado sistema de macros que permite generar código y ejecutar acciones
al momento de compilar el código. Un ejemplo de esto es una librería como
[rox-i18n](http://lib.haxe.org/p/rox-i18n), que facilita la traducción e
internacionalización de aplicaciones. La librería es capaz de leer los strings
de un proyecto y producir automáticamente un archivo de texto listo para
traducir, usando solamente código hecho en Haxe y el sistema de macros.

Si estás interesado en probar código en Haxe sin instalar nada en tu máquina
pasa por [http://try.haxe.org](http://try.haxe.org).

## Haxelib

Una característica interesante de Haxe es que trae un manejador de paquetes,
Haxelib, que simplifica enormemente la labor de descargar, instalar y mantener
versiones de las librerías que se usan en Haxe.

Así, instalar una librería es tan sencillo como escribir "haxelib install openfl"
en la línea de comando de tu computadora, y haxelib se encarga de descargar e
instalar openfl y las dependencias necesarias para la librería.

## OpenFL

Haxe es conocido primordialmente por la librería [OpenFL](http://openfl.org).
OpenFL es un port del API de Adobe Flash a Haxe. Si tienes algún software
escrito para Flash, muy probablemente podrás hacerlo funcionar con OpenFL con
una mínima cantidad de modificaciones. La ventaja de OpenFL está en su capacidad
de compilar ese código a Windows, iOS, Android, Mac y HTML5, entre otras
plataformas.

Lars Doucet, desarrollador de Defender's Quest, y promotor de Haxe de alto
perfil, escribió [este artículo](http://www.gamasutra.com/blogs/LarsDoucet/20140624/219674/Dear_Adobe_Support_Haxe_save_your_Tools.php)
donde escribe a Adobe lo que puede hacer para apoyar a Haxe usando las
herramientas que ya tiene. Es una lectura interesante si has trabajado con
Flash en el pasado.

## Snowkit

Otra librería que ha comenzado a sonar bastante es [Snowkit](http://snowkit.org/),
hecha por el canadiense Sven Bergström. Snowkit es un conjunto de librerías
orientadas a desarrollo nativo (C++) y HTML5, con una filosofía moderna de APIs,
siguiendo principios de programación funcional, y un pipeline de desarrollo
bastante sofisticado.

Snow es la librería base, y Luxe es una capa que ofrece estructuras básicas
específicas para el desarrollo de juegos. Es una buena alternativa a OpenFL.

## HaxeDevelop

[HaxeDevelop](http://haxedevelop.org/) es un IDE para Windows que está orientado
al desarrollo de aplicaciones hechas con Haxe. Esta aplicación se desprende de
FlashDevelop, el cual Haxe adoptó como IDE al punto de hacer su propia aplicación.

HaxeDevelop cuenta con una sección para instalar el software que haga falta para
comenzar a escribir Haxe. Para instalar HaxeDevelop hace falta instalar el
Java Runtime Environment de Oracle.

## Comenzar a hacer aplicaciones en Haxe

 - Descargar e instalar el JDK de Oracle: [http://www.oracle.com/technetwork/java/javase/overview/index.html](http://www.oracle.com/technetwork/java/javase/overview/index.html)
 - Descargar e instalar HaxeDevelop: [http://haxedevelop.org](http://haxedevelop.org)
 - Abrir HaxeDevelop e instalar Haxe y Neko.
 - Abrir una línea de comandos e instalar OpenFL (o Snowkit) escribiendo "haxelib install openfl"
 - Revisar la documentación de OpenFL o de Snowkit para comenzar a hacer un proyecto.
