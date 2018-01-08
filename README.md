# pruebas_carga_CNS
 ---- Artefactos para realizar test de carga----
 
 > Chromedriver: Last Version 
 
 > Software: Jmeter V. 3.2 r1790748 o superior
 
 > Plugins utilizados en Jmeter: 
 
 
 
   - Selenium/WebDriver suport
   - HTTP/2 Sampler
   - jmeter - Java Components
   
   (Para habilitar la opción para ver plugins en Jmeter seguir el siguiente link https://jmeter-plugins.org/wiki/PluginsManager/)
 
 > Pasos para ejecutar la prueba : Descargar archivo comprimido adjunto ("capturas_jmeter".rar )
 
 > URL de prueba: Ej: http://dconvm238:8080/web/convenios-consorcio/compra-tu-soap (Esto se ingresa en el script automatizado "soap.jmx")
 
 ---- Cargar Data de prueba----
 
 > Se ingresan en el archivo adjunto CSV con el siguiente formato
 
    DatoA,DatoB,DatoC,...
    (Rut,Patente,Mail,...)
 
 > Se pueden añadir la cantidad de filas deseadas siguiendo el orden de los datos ingresados en la primera fila
 
 
 ---- Tips Data de prueba----
 
 > Asegurarse que los rut, patente, etc, que listen en el archivo CSV estén relacionados entre sí
 
 > En el caso de listar como dato en el archivo Patente, asegurarse que corresponda a un tipo de vehículo del listado (Es decir, que NO sea SIN MOTOR)
 
                    
