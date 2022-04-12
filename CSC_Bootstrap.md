Vamos a cambiar las propiedades, en este caso de los colores, de Bootstrap.

----

1. Asociamos BootStrap desde NPM
    Dentro del terminal: 

   **npm init -v**

   **npm install bootstrap**

----
2. Creamos fichero style.scss en el que importamos hacía el fichero bootstrap.scss:

**@import "./node_modules/bootstrap/scss/bootstrap.scss";**

Compilamos SCSS

----

3. Al final del body añadiremos los Scripts:

 **<sript src="./node_modules/@popperjs/core/dist/umd/popper-base.min.js"></sript>**
  **<script src="./node_modules/bootstrap/dist/js/bootstrap.min.js"></script>**

----
  
  El color de bootstrap "success" es verde:
  
![Alt text](primera_captura.PNG "primera captura")

Modificamos en style.scss:

![Alt text](segunda_Captura.PNG "segunda captura")

Y podremos ver como se ha modificado el color!

![Alt text](tercera_captura.PNG "tercera captura")


Para poder crear un color: 
![Alt_text](nombre_captura.PNG "nombre captura)

Modificamos el scss:
![Alt_text](color_captura.PNG "color captura)
