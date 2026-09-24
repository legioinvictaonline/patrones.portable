# Lenguajes de patrones

Material de trabajo interno. Se abre con contraseña.

## Cómo se usa

Abrir el enlace, escribir la contraseña y listo. No hace falta cuenta, instalar nada ni descargar nada.

## Cómo está protegido

El contenido va **cifrado con AES-GCM**. La clave se deriva de la contraseña con PBKDF2-SHA256 y 250,000 iteraciones, y el descifrado ocurre en el navegador de quien abre.

No es una puerta cosmética: sin la contraseña, lo que se descarga es ruido. El texto no está en el HTML.

Las láminas van como archivos y no están cifradas — protegerlas costaría descifrar 49 MB al abrir. Quedan resguardadas por no estar enlazadas y por `robots.txt`.

## Qué contiene

Cinco lenguajes de patrones, navegables por escala, con búsqueda y enlaces entre patrones mayores y menores. La atribución de cada fuente viene dentro de cada patrón.

## Cómo se regenera

Ver la nota `publicar con contraseña en GitHub Pages` en el vault.

El contenido va **congelado**: no se actualiza cuando cambian las notas. Para reflejar cambios hay que regenerar y volver a subir.
