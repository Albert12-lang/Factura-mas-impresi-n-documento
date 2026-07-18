# Factura-mas-impresi-n-documento


## Introducción
El objetivo de está actividad es poder desarrollar un sistema de facturación web elaborado con JavaScript, el sistema permite seleccionar productos o servicios desde una lista, calcular automáticamente el precio según la cantidad ingresada y generar el subtotal, el IVA y el total a pagar.
El desarrollo del sistema de facturación en JavaScript, continuando con el apartado del código se irá implementando las sintaxis y códigos que permitan visualizar en la tabla de productos, la descripción, el código de estos mismos, su valor único, la cantidad que el usuario se llevará y poder eliminar el producto si el usuario no quiere comprar algún producto que ya se registro.


## Objetivos
El objetivo es que los estudiantes implementen la funcionalidad usando vectores (arreglos) para almacenar y manipular los productos agregados a la factura. 
Documentar el funcionamiento del sistema de facturación desarrollado mediante HTML, CSS y JavaScript, describiendo su estructura, características y proceso de cálculo.
Desarrollando el sistema de facturación web utilizando JavaScript para completar la tabla de productos.


## Objetivos específicos
Explicar la estructura de la interfaz gráfica del sistema.
Describir el funcionamiento del código JavaScript encargado de gestionar los productos y los cálculos.
Describir el funcionamiento del código JavaScript encargado de gestionar los productos y los cálculos.
Implementar el código completo de JavaScript en la tabla de artículos.


## Desarrollo
El sistema de facturación está hecho con el archivo HTML, Css y JavaScript, que implementa la lógica de funcionamiento.
El sistema tendrá un arreglo que almacena los productos disponibles con su código, precio y descripción.
Cuando el cliente selecciona el producto, el sistema obtiene automáticamente su precio, cantidad del producto y calcula el valor total.
Completar el código de JavaScript con la implementación de los códigos de los productos, la descripción, valor único, la cantidad, el total y la acción de eliminar un producto con su valor ya registrado en la tabla de artículos.
Y la última implementación tener un botón donde se imprima la factura en un documento pdf.


## Preguntas
¿Cómo se implementa la funcionalidad para agregar y mostrar los productos en la tabla de la factura?
Se fueron utilizando arreglos como  el de facturaDetalles, que permite almacenar la información de cada producto agregando a la factura el código, la cantidad, el precio, el iva y el total.
Al momento de pulsar el botón (agregar), el sistema recibe los datos del producto seleccionado y los guarda en el arreglo (push), después se llama al mostrarTabla, que recorre el arreglo y genera a la tabla usando el InnerHTML, mostrando todos los datos.
¿De qué manera se realizó la eliminación de un producto y cómo se actualizan automáticamente el subtotal, el IVA y el total a pagar?
En la tabla cada que se genere un producto tendrá el botón (eliminar) que ejecuta la función de eliminarProducto(index), usa el método (splice) para eliminar el producto que se quiera quitar de la facturaDetalles, después se actualiza la tabla con esto recalculando todos los cálculos anteriores. 
¿Qué funciones y estructuras de JavaScript se utilizaron para gestionar los productos y realizar los cálculos de la factura?
El sistema usa el arreglo (vectores) para almacenar tanto los productos como la factura, emplea funciones como cargarProductos, mostrarTabla y eliminarProducto para organizar el código, facilitar su mantenimiento, recorrer el arreglo se usa el ciclo (for), mientras los métodos push, splicer permiten agregar y eliminar elementos.
Los eventos changer y click actualizan automáticamente el precio, el total de cada producto, el subtotal, el iva y el total a pagar.


## Conclusión
El objetivo de desarrollar el sistema es poder permitir que vaya a ver una automatización en la compra de los productos con esto llegando a ser más rápido y facilitando el procesos administrativo.
En la elaboración del código se implementó una nueva función que permite poder mostrar la tabla y eliminar los productos  con ello recalcular los valores que se fueron quitando de la factura.
Se pudo implementar la correcta elaboración del código que va a permitir ver los artículos de la tabla a los usuarios, también con ello ver qué artículo se lleva, cuanta es la cantidad del mismo artículo y la eliminación de estos mismo.


## Autores 
1. Alavera Mejía Wellington Zinedine. 
2. Gualpa Gonzalez Jhon Jairo. 
3. Landivar López Francisco Alberto. 
4. Semper Ordóñez Ismael Jared. 
5. Ocampo Rivera Christopher Alexis.
