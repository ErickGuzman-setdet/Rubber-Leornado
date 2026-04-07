Todos alguna vez hemos querido realizar un USB-Rubber Ducky, con el Arduino podemos realizar esta misma metodología para poder controlar el teclado y realizar instrucciones al conectar a un pc.


Tenemos que entender que para realizar este proyecto se requiere que nuestro Arduino tenga HID (Human Interface Device) de esta manera tener acceso a manejar teclado y mouse/ratón del dispositivo que se vaya a utilizar.

Cabe aclarar que este código lo configure para que abra una ventana de PowerShell, y desde ahí poder descargar un archivo, este archivo no es mas que una carga útil para tomar control de un Windows, pero en si podemos configurar el código para realizar lo que queremos realizar. Esta carga útil se obtiene con el framework metasploit que nos permite realizar ataques con vulnerabilidades conocidas. Simplemente cambiamos el URL para poder indicar al PowerShell de donde descargarlo y ejecutarlo.
