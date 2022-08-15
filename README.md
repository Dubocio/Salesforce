# Ejercicio 2.

## 1. ¿Qué es un servidor HTTP?

            Es un software que forma parte del servidor y tiene como misión principal devolver información (páginas) cuando recibe peticiones por parte de los usuarios.

## 2. ¿Qué son los verbos HTTP? Mencionar los más conocidos

            Son el método de petición que define HTTP para indicar la acción a realizar para un recurso determinado. Los más populares son: el método GET que solicita la representacion de un recurso específico y
            el método POST que envia informacion a un recurso, modificándolo y el método DELETE que sirve para borrar informacion de un recurso.

## 3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

        HTTP se basa en un modelo solicitud / respuesta, de modo que hay dos tipos de mensajes HTTP: la solicitud(Request) y la respuesta(Response). El navegador abre una conexión a un servidor y realiza una solicitud. El servidor procesa la solicitud del cliente y devuelve una respuesta. Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc.

## 4. ¿Qué es un queryString? (En el contexto de una url)

        Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web.

## 5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

        Los códigos de estado HTTP son como notas cortas de un servidor que se insertan en una página web. En realidad no son parte del contenido del sitio. En su lugar, son mensajes del servidor que te permiten saber cómo fueron las cosas cuando recibió la solicitud de ver una determinada página. Los posibles valores devueltos son:

                    100s: Códigos informativos que indican que la solicitud iniciada por el navegador continúa.
                    200s: Los códigos con éxito regresaron cuando la solicitud del navegador fue recibida, entendida y procesada por el servidor.
                    300s: Códigos de redireccionamiento devueltos cuando un nuevo recurso ha sido sustituido por el recurso solicitado.
                    400s: Códigos de error del cliente que indican que hubo un problema con la solicitud.
                    500s: Códigos de error del servidor que indican que la solicitud fue aceptada, pero que un error en el servidor impidió que se cumpliera.

## 6. ¿Cómo se envía la data en un Get y cómo en un POST?

        La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).

## 7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

        Utiliza el verbo GET y nos devuelve un código de estado, indicando si la petición ha sido exitosa, o no, y debido a que.

## 8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles

        XML (Extensible Markup Language) es uno de los formatos más utilizados para el intercambio de información entre sistemas. El formato de este estándar está basado en texto para representar información estructurada: datos, documentos, configuración, etc.
        Todas las etiquetas se deben cerrar y si existe un error en el XML las herramientas que los procesan darán error.
        Un ejemplo:
                    <pieza tipo="A">
                        <nombre>Tornillo</nombre>
                        <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras
                        </descripcion>
                        <caracateristica>
                            <tipo>metal</tipo>
                            <tamanyo>10</tamanyo>
                        </caracateristica>
                        <vacio></vacio>
                    </pieza>

        JSON (JavaScript Object Notation) está construido por una colección de pares de nombre y valor o por una lista ordenada de valores. En muchos lenguajes de programación tenemos elementos parecidos como pueden ser los objetos, una estructura, un diccionario, un array. Este formato es el que se suele utilizar en el los servicios web REST en la actualidad.
        Un ejemplo:
                    {
                        “pieza”: {
                            “tipo”: “A”
                            “nombre”: “Tornillo”,
                            “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
                            “caracteristica”: {
                                “tipo”: “metal”
                                “tamanyo”: 10
                            },
                            “vacio”: “”
                        }
                    }

## 9. Explicar brevemente el estándar SOAP

        SOAP (originalmente las siglas de Simple Object Access Protocol) es un protocolo estándar que define cómo dos objetos en diferentes procesos pueden comunicarse por medio de intercambio de datos XML. Es esencial para los servicios web, interfaces a través de las cuales un dispositivo puede hacer uso del servicio de un servidor. Los buscadores, las tiendas en línea y otros muchos servicios en Internet funcionan a través de dichos servicios web, y SOAP es uno de los protocolos que lo hacen posible.

## 10. Explicar brevemente el estándar REST Full

        Es un servicio que funciona como un estándar para compartir información, en un sistema de doble vía: Consulta y Respuesta (Request => Response).
        Al consultar una API se deben especificar parámetros de consulta para que el servicio sepa lo que queremos consultar, basado en una estructura previamente definida provista por el API por medio de una documentación.
        La arquitectura REST al trabajar sobre el protocolo HTTP, los procedimientos o métodos de comunicación son los mismos que HTTP, siendo los principales: GET, POST, PUT, DELETE. Otros métodos que se utilizan en RESTful API son OPTIONS y HEAD. Este último se emplea para pasar parámetros de validación, autorización y tipo de procesamiento, entre otras funciones.
        Otro componente de un RESTful API es el “HTTP Status Code”, que le informa al cliente o consumidor del API que debe hacer con la respuesta recibida. Estos son una referencia universal de resultado, es decir, al momento de diseñar un RESTful API toma en cuenta utilizar el “Status Code” de forma correcta.

## 11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

        Los headers en un request son los parámetros que se envían en una petición o respuesta HTTP al cliente o al servidor para proporcionar información esencial sobre la transacción en curso. Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado.

# Ejercicio 3.

## 1. [![ejercicio-1-get.jpg](https://i.postimg.cc/QC30vY6c/ejercicio-1-get.jpg)](https://postimg.cc/34tXv1Qw)

## 2. [![ejercicio-2-post.jpg](https://i.postimg.cc/rmWfn298/ejercicio-2-post.jpg)](https://postimg.cc/47fvyMMM)

## 3. [![ejercicio-3-post.jpg](https://i.postimg.cc/hGXymdzQ/ejercicio-3-post.jpg)](https://postimg.cc/t1HNQ7z9)

            La diferencia con la primer consulta, es que me trae la base con el nuevo dato que agregue con el metodo POST en el segundo ejercicio.
