# Ud2_Ejemplo3
_Ejemplo 3 de la Unidad 2._ 

Vemos la diferencia entre _center_, _centerCrop_ y _centerInside_, para ello sólo hemos de fijarnos en el fichero _main_activity.xml_
y en concreto en las siguientes líneas:

```
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/grand_canyon"
        android:scaleType="centerInside"
        ... />
 ```
Donde podemos ver que el nombre de la imagen es _grand_canyon_ y se puede encontrar en el directorio _drawable_.
Notad cómo accedemos al recurso _drawable_ usando el símbolo @.

Si vamos cambiando entre _center_, _centerCrop_ y _centerInside_tanto en el atributo _scaleType_ podremos ver la diferencia entre ellos.

_Imagen de Pixabay.com (Licencia CC0)_
