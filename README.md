# sesion7-tarea-individual
Conociendo el GRUB

Empecemos a investigar acerca de grub…
Lo primero será recuperar tu viejo manual de grub. 

A continuación, vamos a familiarizarnos con los ficheros implicados.
Accede a Ubuntu y lanza el comando "grep menuentry /boot/grub/grub.cfg"

Te recuerdo que el comando grep lo que hace es leer todo el fichero que se le ha indicado (/boot/grub/grub.cfg) e imprimir sólo aquellas líneas que contienen la expresión indicada (menuentry). Haz una captura y explica lo que ves. 

Con el ejercicio anterior ya hemos visto que la información se guarda en /boot/grub/grub.cfg, no obstante este fichero es generado automáticamente y no debe ser manipulado. El fichero previsto para ser editado es /etc/default/grub.

Accede a tu Ubuntu y modifica estas opciones para que aparezca marcado Windows directamente en el arranque. Indica cómo quedan los parámetros. 

...
