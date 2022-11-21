# Evaluación Práctica 

## ACTIVIDADES

- Ejercicio 1 

	Se realizo la instalación del ambiente para el desarrollo del trabajo práctico (Visual Studio Code y GIT y GIT Bash).
    
 - Ejercicio 2 
  	1. ¿Qué es un servidor HTTP? 

    	Con "Servidor web" podemos referirnos a hardware o software, o a ambos trabajando juntos. En cuanto a Hardware, un servidor web es una computadora que almacena 	el software de servidor web, y los archivos que componen un sitio web (por ejemplo, documentos HTML, imágenes, hojas de estilos CSS y archivos JavaScript). 
    	En cuanto a Software permite que los usuarios que quieren ver una página/sito web en su navegador puedan hacerlo.

  	2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

    	Son métodos de petición para indicar la acción que se desea realizar para un recurso determinado. Los mas conocidos son: 
	
      	 * GET: Obtiene el recurso indicado. Es el método que se utiliza cuando se pide el contenido de una página web, por ejemplo.
      	 * HEAD: Similar a GET, pero no se obtiene el cuerpo de respuesta, únicamente los metadatos de la cabecera.
      	 * POST: Añade datos al servidor. Siempre es un método de creación.
      	 * PUT: Es una solicitud para almacenar la entidad suministrada en el URI indicado. Si la entidad no existe, se crea. Si la entidad existe, se actualiza.
      	 * DELETE: Elimina el recurso indicado.
      	 * TRACE: Devolverá la misma información que se ha enviado en la solicitud. Es una especie de eco. Sirve para comprobar si la solicitud se ha visto modificada por servidores intermedios.
      	 * OPTIONS: Devuelve los métodos HTTP soportados por el servidor para la URL especificada.
      	 * CONNECT: Convierte la solicitud en un tunel TCP/IP.Normalmente se usa para crear comunicaciones HTTPS a través de proxys HTTP sin encriptación.
      	 * PATCH: Aplica modificaciones parciales al recurso especificado.

  	3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
  
  		Las Request HTTP son mensajes enviados por un cliente, para iniciar una acción en el servidor. Una vez que el servidor ha recibido y procesado la 		  solicitud, éste debe devolver un Response HTTP hacia el cliente. El mensaje de respuesta se compone de una línea de estado y cero o más campos de 			cabecera, seguido por una línea vacía. También puede tener opcionalmente un cuerpo del mensaje.
  	 	Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página 		solicitada, del servidor, etc.

  	4. ¿Qué es un queryString? (En el contexto de una url)

   		Es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web. permiten acceder a páginas web dinámicas con distintas variables 		       consiguiendo    así que las páginas web no estén compuestas de decenas de directorios y permitiendo que su estructura esté basada en URLs amigables.

  	5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

    	Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. 
	Las respuestas se agrupan en cinco clases:
	
		* 100s: Códigos informativos que indican que la solicitud iniciada por el navegador continúa.
		* 200s: Los códigos con éxito regresaron cuando la solicitud del navegador fue recibida, entendida y procesada por el servidor.
		* 300s: Códigos de redireccionamiento devueltos cuando un nuevo recurso ha sido sustituido por el recurso solicitado.
		* 400s: Códigos de error del cliente que indican que hubo un problema con la solicitud.
		* 500s: Códigos de error del servidor que indican que la solicitud fue aceptada, pero que un error en el servidor impidió que se cumpliera.


  	6. ¿Cómo se envía la data en un Get y cómo en un POST? 
  	
  	El método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).

  7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?

    El verbo GET es el que utiliza el navegador cuando accedemos a una pagina.


  8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
      •	JSON: es un formato de datos basado en la sintaxis de objeto de JavaScript, se utiliza para estructurar datos en forma de texto y permite el intercambio de                   información entre aplicaciones de manera sencilla, liviana y rápida. 
              ```csharp
                  {
	                  "firstName": "John",
	                  "lastName": "Smith",
	                  "address": {
	                              "streetAddress": "21 2nd Street",
	                              "city": "New York",
	                              "state": "NY",
	                              "postalCode": 10021
	                 },
	                "phoneNumbers": [
	                    "212-732-1234",
	                    "646-123-4567"
	                    ]
	                }
              ```

      • XML: es un lenguaje de marcado similar a HTML. Significa Extensible Markup Language (Lenguaje de Marcado Extensible) y es una especificación de W3C como                    lenguaje de marcado de propósito general. Esto significa que, a diferencia de otros lenguajes de marcado, XML no está predefinido, por lo que debes                    definir tus propias etiquetas. El propósito principal del lenguaje es compartir datos a través de diferentes sistemas, como Internet.
              ```csharp
                  <libreria> 
                    <libro>
                      <autores>
                           <autor>Elizabeth Castro</autor> 
                      <autores>
                      <titulo>XML Guía de Aprendizaje</titulo> 
                      <precio moneda="euros">30</precio>
                      <descriptores>
                          <descriptor>lenguajes<descriptor>
                          <descriptor>XML<descriptor>
                      <descriptores>
             
                   </libro> 
                   <libro>
                     <autores>
                          <autor>Benoit Marchal</autor> 
                     <autores>
                     <titulo>XML con ejemplos</titulo> 
                     <precio moneda="euros">45</precio>
                     <descriptores>
                        <descriptor>lenguajes<descriptor>
                        <descriptor>XML<descriptor>
                     <descriptores>
                   </libro> 
                </libreria>
	                
              ```

  9.	Explicar brevemente el estándar SOAP

     SOAP es un protocolo estándar que se creó originalmente para posibilitar la comunicación entre las aplicaciones que se diseñaban con diferentes                        lenguajes y en distintas plataformas por medio de intercambio de datos XML.

 10.	Explicar brevemente el estándar REST Full

    Es una interfaz que dos sistemas de computación utilizan para intercambiar información de manera mas segura a través de internet. 
    
 11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

- Ejercicio 3 

