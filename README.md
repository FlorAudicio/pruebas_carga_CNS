# pruebas_carga_CNS
 ---- Artefactos para realizar test de carga----
 
 > Chromedriver: Last Version 
 
 > Software: Jmeter V. 3.2 r1790748 o superior (requiere tener instalado el JDK)
 
 > Plugins utilizados en Jmeter: 
 
 
   - Selenium/WebDriver suport
   - HTTP/2 Sampler
   - jmeter - Java Components
   
   (Para habilitar la opción para ver plugins en Jmeter seguir el siguiente link https://jmeter-plugins.org/wiki/PluginsManager/)
 
 > Pasos para ejecutar la prueba : Descargar archivo comprimido adjunto ("capturas_jmeter".rar )
 
 > URL de prueba: En el script se basó en la siguiente URL http://dconvm238:8080/web/convenios-consorcio/compra-tu-soap, sin embargo esto depende del ambiente y es totalmente modificable (Esto se ingresa en el script automatizado "soap.jmx")
 
 > Este script se realizó sobre el sitio responsivo de SOAP, sin embargo se puede modificar teniendo cuidado en modificar también el nombre de los campos correspondientes en el script.
 
 > Este script sigue el flujo de SOAP responsivo paso 1 y 2 (solicitaron que fuera sin pago para las pruebas lo que implica sólo estos dos pasos), por lo tanto, en caso de desear que el flujo continue se deben agregar al script los nuevos botones y campos sobre los cuales hacer click e ingresar información (se recomienda buscar los campos y botones mediante el ID). Para agregar nuevas funciones al script apoyarse en la siguiente documentación: https://jmeter-plugins.org/wiki/WebDriverSampler/.
 
 ---- Cargar Data de prueba----
 
 > Se ingresan en el archivo adjunto CSV con el siguiente formato
 
    DatoA,DatoB,DatoC,...
    (Rut,Patente,Mail,...)
    
 > Para cada campo nuevo que se agregue en el archivo CSV (recordar que el campo nuevo se agrega separado por " , " de los demás) estos se deben agregar también en la configuración del CSV y el script en Jmeter (ver el archivo "capturas_jmeter.rar" para saber donde y como)
 
 > Se pueden añadir la cantidad de filas deseadas siguiendo el orden de los datos ingresados en la primera fila (revisar archivo CSV adjunto)
 
 
 ---- Tips Data de prueba----
 
 > Asegurarse que los rut, patente, etc, que listen en el archivo CSV estén relacionados entre sí
 
 > En el caso de listar como dato en el archivo Patente, asegurarse que corresponda a un tipo de vehículo del listado (Es decir, que NO sea SIN MOTOR)
 
 
---- BackUp----

> Leonel Saá (principal) (célula de SOAP, líder Elias Gárate)
> Lorens Sepúlveda (secundario) (célula de SOAP, líder Elias Gárate)
> flor.audicio@tinet.cl
                    
