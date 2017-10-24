# Comandos VIM

* h - Se desplaza un espacio a la izquierda.
* l - Se desplaza un espacio a la derecha.
* k - Se desplaza una línea hacia arriba.
* j - Se desplaza una línea hacia abajo.
* 7h - Se desplaza siete caracteres hacía la izquierda.
* 17j - Se desplaza diecisiete líneas hacia abajo.
* 4k - Se desplaza cuatro líneas hacia arriba.
* nh/l/j/k - Se desplaza n espacios o líneas.
* 0 - Se dirige al primer carácter de la línea.
* $ - Se dirige al último carácter de la línea.-
* G - Se dirige a la última línea del archivo.
* nG - Se dirige a la n línea del archivo.
* w - Se desplaza al principio de la siguiente palabra.
* 5e - Mueve al final de la quinta palabra a partir de la posición del cursor.
* Ctrl+F - Hace un desplazamiento del texto hacia adelante (abajo).
* Ctrl+B - Hace un desplazamiento del texto hacia atrás (arriba).

## Comandos de inserción

* a - Agrega texto después del cursor y entra al modo de inserción.
* A - Agrega texto al final de la línea y entra al modo de inserción.
* i - Inserta texto antes del cursor y entra al modo de inserción.
* I - Inserta texto al inicio de la línea y entra al modo de inserción.
* o - Abre una línea debajo del cursor y entra al modo de inserción.
* O - Abre una línea encima del cursor y entra al modo de inserción.

## Comandos para suprimir

* nx - Suprimir n caracteres, a partir del que está bajo el cursor.
* n+Delete Key (Supr) - Lo mismo que nx.
* ndw - Suprimir n palabras.
* d$ - Suprimir hasta el final de la línea.
* ndd - Suprimir n líneas.

## Comandos de deshacer y reemplazar

* u - Revierte la última modificación.
* U - Revierte todas las modificaciones hechas en la línea actual.
* nr - Reemplaza n caracteres.
* cw - Reemplaza una palabra.
* c$ - Reemplaza el resto de una línea.
* R - Establece el modo de reemplazo para hacer sustituciones de forma ilimitada.

## Comandos para encontrar texto

* / - Buscar una cadena de caracteres a partir del cursor hacia el fin del archivo.
* ? - Buscar una cadena de caracteres a partir del cursor hacia el inicio del archivo.
* n - Ir a la siguiente cadena que coincida con la que se busca en el archivo.

## Comandos para guardar y salir

* :w - Guardar (salvar) el archivo.
* :q! - Salir sin guardar.
* :wq - Guardar todas las modificaciones y salir.
* :wq nuevo nombre_archivo - Guardar el archivo con otro nombre.
* :help - Abrir la ventana de ayuda.

