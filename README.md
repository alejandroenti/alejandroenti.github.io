# Página web de ejemplo para la asignatura de Lenguaje de Marcas (M04UF1)

Además, vamos a aprovechar para hablar de Markdown.

## ¿Qué es este repositorio?

Aquí almacenaremos la página web estática de la asignatura así como algunos ejemplos de Markdown, CSS, JavaScript, etc.

- Dos **astericos** significa BOLD.
- Un *asterico* significa ITALIC.
- Un _guión_ _bajo_ significa también ITALIC.
- Para ***BOLD ITALIC*** tres astericos.
- Guión seguido de espacio para hacer un item de lista.

## Ejemplo de lista de tareas (tasks)

- [ ] Aprender HTML
- [ ] Aprender CSS
- [ ] Aprender JavaScript
- [x] Aprender MySQL

## Preguntas actividad final

- ***¿Qué es HTML? ¿CSS? ¿Javascript?***

	**HTML** es el lenguaje estándar que se utiliza para la realización estructural de páginas web en la actualidad. Sus siglas significan *HyperText Markup Language*. Este lenguaje piensa en el hipertexto, es decir, que lás páginas web están enlazadas entre sí y nos podemos mover entre ellas. Hoy en día utilizamos *XHTML*, XML combinado con HTML5.
	
	**CSS** es un lenguaje que nos sirve para aplicar estilos en cascada. Sus siglas significan *Cascading Style Sheets*. Este lenguaje nos permite aplicar colores, efectos, animaciones, etc. a un contenido.
	
	**JavaScript** es un lenguaje de programación que, junto a los 2 anteriores, forma el core de las tecnologias web hoy en día. Es un lenguaje de *alto nivel* (estamos más cercano al lenguaje humano que al lenguaje máquina) y es *interpretado* (se compila en tiempo real). Además, JavaScript es de *tipado dinámico* (podemos cambiar el tipo de una variable cuando queramos).
- ***¿Qué es el formato Markdown?***

	El formato **Markdown** es un lenguaje de marcas que nos permite la realización de textos formateados usando un editor cualquiera de texto. De esta forma podemos crear documentos como este Readme.me, con negrita, parráfos, listas, etc.
- ***¿Qué es el formato JSON? ¿Cómo se convierte un objeto a JSON? ¿Y JSON a un objeto?***

	El formato **JSON** es estándar de intercambio de datos que es legible para los humanos. En él se almacena y tramiste información mediante el par *clave - valor*. Para **convertir un objecto a JSON** debemos aplicar el método *stringify* del objeto *JSON* para poderlo enviar por la red. En cambio, para **convertir un JSON en un objeto** debemos primero recibir el JSON mediante una promesa y entonces aplicarle el método *json()* por el que pasará a ser un objeto.