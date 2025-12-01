1. Inicie la terminal
2. Cree un directorio con el nombre capitulo3. 
   mkdir capitulo3
3. Vaya a su directorio capitulo3. 
   cd capitulo3
4. Cree el árbol dir1/dir2/dir3/dir4 . 
   mkdir -p dir1/dir2/dir3/dir4
5. Liste el contenido del directorio actual de forma recursiva.
   ls -R / tree -L Numero niveles
6. Suprima el directorio dir1. ¿Es posible?
rm -r di1r/
7. Suprima el árbol de directorios dir1/dir2/dir3/dir4, después verifíquelo listando el directorio actual de forma recursiva.

tree -L 3 ~

8. Cree ahora el árbol siguiente en su directorio actual (/home/tux/capítulo3 ) sin cambiar de directorio:
![alt text](image.png) mkdir -p /home....
1. Copie el archivo /etc/services en su directorio capítulo3. cp
2.  ¿A quién pertenece el archivo que acaba de copiar?  ¿Cuál es la fecha de la última modificación?ls -l
3.  Cree archivos que no contengan ningún dato y con los nombres siguientes: triangulo, redondo, cuadrado, rectángulo, verde y azul. touch triangulo redondo ....
4.  Mueva el archivo redondo al directorio curva y los archivos, triángulo, cuadrado, rectángulo al directorio ángulo. mv redondo /ruta