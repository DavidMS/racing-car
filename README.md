Racing Car Katas
=================

En este repositorio encontrará código de inicio para cinco problemas distintos. Podrían ser código heredado de una base de código heredada. Ahora desea escribir pruebas unitarias para ellos, y eso es más difícil de lo necesario. Todos los fragmentos de código no siguen uno o más de los principios SOLID.

Para cada ejercicio, debe identificar qué principios SOLID no sigue el código. Solo hay una clase para la que estás interesado en hacer tests en este momento. Como primer paso, intente realizar algún tipo de prueba antes de cambiar la clase. Si las pruebas son difíciles de escribir, ¿se debe a los problemas con los principios SOLID?

Cuando tenga algún tipo de prueba en la que apoyarse, refactorice el código y hágalo comprobable. Al refactorizar, tenga cuidado de no alterar la funcionalidad o cambiar las interfaces en las que otro código de cliente pueda confiar. (Imagine que hay un código de cliente en otro repositorio que no puede ver en este momento). Agregue más pruebas para cubrir la funcionalidad de la clase en particular que se le ha pedido que realice la prueba.

Aplique el estilo y el marco de pruebas unitarias con los que se sienta más cómodo. Puede optar por utilizar stubs o simulacros o ninguno en absoluto. Si lo hace, puede utilizar la herramienta de mock que prefiera.

1. ** Ejercicio TirePressureMonitoringSystem **: escriba las pruebas unitarias para la clase de alarma. La clase de alarma está diseñada para monitorear la presión de los neumáticos y establecer una alarma si la presión cae fuera del rango esperado. La clase Sensor proporcionada para el ejercicio simula el comportamiento de un sensor de neumático real, proporcionando valores aleatorios pero realistas.

2. ** Ejercicio UnicodeFileToHtmlTextConverter **: escriba las pruebas unitarias para la clase UnicodeFileToHtmlTextConverter. La clase UnicodeFileToHtmlTextConverter está diseñada para reformatear un archivo de texto sin formato para mostrarlo en un navegador. También hay una clase adicional "HtmlPagesConverter" que es un poco más difícil de probar. No solo convierte el texto de un archivo a html, sino que también admite la paginación. Está pensado como un ejercicio de seguimiento.

3. ** Ejercicio TicketDispenser **: escriba las pruebas unitarias para el TicketDispenser. La clase TicketDispenser está diseñada para administrar un sistema de colas en una tienda. Puede haber más de un distribuidor de tickets, pero el mismo ticket no debe emitirse a dos clientes diferentes.

4. ** Ejercicio TelemetrySystem **: escriba las pruebas unitarias para la clase TelemetryDiagnosticControls. La responsabilidad de la clase TelemetryDiagnosticControls es establecer una conexión con el servidor de telemetría (a través de TelemetryClient), enviar una solicitud de diagnóstico y recibir con éxito la respuesta que contiene la información de diagnóstico. La clase TelemetryClient proporcionada para el ejercicio falsifica el comportamiento de la clase TelemetryClient real y puede responder con la información de diagnóstico o con una secuencia aleatoria. La clase TelemetryClient real se conectaría y se comunicaría con el servidor de telemetría a través de tcp / ip.

5. ** Ejercicio de tabla de clasificación **: (tenga en cuenta que este ejercicio aún se está desarrollando) Escriba las pruebas unitarias para la clase de tabla de clasificación, incluidas las carreras con autos sin conductor. La tabla de clasificación calcula los puntos y las clasificaciones de los pilotos en función de los resultados de varias carreras.

