# Payload del bashbunny basado en el de hack5 para rubber ducky

El payload originalmente estaba escrito para el bashbunny, se adapto para  
el usb rubber ducky.

## Cosas que se modificaron y se agregaron

- Se mejoro la apariencia de la pantalla de bloqueo
- En el payload ahora podemos extraer el fondo actual  
  y agregarlo como pantalla de bloqueo
- Podemos agregar un dispositivo de almacenamiento  
  para de la carpeta phishing adaptando un hub usb

## Cosas a tener en cuenta

El archivo pw.js tiene cargado el fondo que se va inyectar en la pantalla de bloqueo,  
es importante que si se va usar mas de una vez borres el contenido que se agrega  
despues de la linea 1, ya que si no se hace el payload va seguir agregando lineas  
ya existentes
