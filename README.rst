=============
LS1 MMASS Doc
=============

.. contents:: Contenidos

Instalacion en Clientes
=======================

El MMASS sólo se instala en el  servidor. Las PC-clientes deben tener en el escritorio un acceso directo al ejecutable que se encuentra en \\\\HDX2\\Soft\\

Con el botón derecho del mouse se arrastra el ejecutable al escritorio de la PC-clientes y se crea el acces directo. 

Carga de Ordenes de Publicidad
==============================

Las órdenes de publicidad (OP) se cargan usando dos pestañas. Más abajo usaré capturas de pantallas para mostrarlo mejor. 

Algunos conceptos: Los avisos perteneces a un anunciantes y los anunciantes pertenecen a una Agencia de Publicidad. Abajo las relaciones.

- Aviso **belongs to** Anunciante **belongs to** Agencia de Publicidad. 
- Agencia de Publicidad **has many** Anunciantes **has many** OP. 

Ejemplos: Aviso -> "Petrobras presenta" (un audio de 2s), -> **pertenece a** Petrobas (anunciante) -> **pertenece a** Agencia de Publicidad. 

Aviso -> "Petrobras presento" (un audio de 2s), -> **pertenece a** Petrobas (anunciante) -> **pertenece a** Agencia de Publicidad. 

Aviso -> "Personal Pack Primavera" (un audio de 7s), -> **pertenece a** Personal (anunciante) -> **pertenece a** Agencia de Publicidad. 

Aviso -> "Personal Pack Verano" (un audio de 9s), -> **pertenece a** Personal (anunciante) -> **pertenece a** Agencia de Publicidad. 

En nuestro caso, siempre usamos la misma agencia de publicidad. 

FAQ
===

- Un aviso sale en distintos programas y días diferentes, ¿cuantas OP se necesitan?
- Rta: Solo una
- ¿Que son los renglones de las OP?
- Rta: En las OP, un audio puede salir en dos programas distintos, entonces necesito dos renglones. Un renglon por programa. 
- Si un audio sale en un mismo programa, pero se repite en distintos días, ¿cuantos renglones necesito?
- Rta: Un solo renglon. En el renglon indicamos cuantos spot salen en el programa por día. 
- Si un aviso sale en dos meses, ¿cuantas OP necesitamos?
- Rta: debido a que hay una facturación mensual usamos dos OP. Cuando numeramos las OP usamos numeros como 8455/1 y 8455/2. Así sabemos que hicimos dos OP para el mismo aviso. 
- ¿Quién/es debe cargar las OP? 
- Rta: Las personas designadas de puesta en el aire. 
- ¿Que es una certificación horaria?
- Rta: Una vez por mes, verificamos tener bien un reporte que da el MMASS, dónde dice que avisos salieron al aire y su duración real. El reporte nosotros no lo imprimimos, pero si lo observamos. Por ejemplo, en una OP dice que un audio dura 15s pero cuando se reproduce la duración es de 21s. Este reporte se usa para cuando la radio factura a la agencia de publicidad. 
