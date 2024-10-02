# Tarea: Explorando el Framework Cowboy en Erlang
Jorge Luis Castro Alvarado
## **Preguntas Teóricas**
Fundamentos de Erlang:

    Alta concurrencia y escalabilidad en Erlang:
    Erlang maneja la concurrencia con un modelo basado en procesos ligeros y aislados que no comparten memoria, lo que permite ejecutar millones de procesos en paralelo. Su agendador y balanceo de carga entre nodos facilitan la escalabilidad horizontal.

    Modelo de actores en Erlang:
    En Erlang, cada proceso es un actor que se comunica con otros mediante el envío de mensajes asíncronos. Este modelo simplifica la gestión de procesos concurrentes y evita bloqueos y condiciones de carrera.

Características de Cowboy:

    Ventajas de Cowboy como servidor HTTP:
    Cowboy es liviano, altamente concurrente y diseñado para gestionar muchas conexiones simultáneas con baja latencia, lo que lo hace ideal para aplicaciones de tiempo real y alta disponibilidad.

    Manejo eficiente de conexiones concurrentes en Cowboy:
    Cowboy utiliza procesos ligeros de Erlang para cada conexión, lo que permite manejar miles de conexiones concurrentes sin saturar los recursos del sistema.

Uso en la Industria:

    Empresas que usan Erlang/Cowboy:
        WhatsApp: Lo utiliza para gestionar millones de conexiones simultáneas en su plataforma de mensajería.
   
    Aplicaciones donde Cowboy es menos común:
    Cowboy es menos común en aplicaciones de backend tradicionales, donde se prefieren lenguajes y frameworks más orientados a servicios empresariales y no tanto a concurrencia masiva.

Integración con Otros Frameworks:

    Integración de Cowboy con Phoenix en Elixir:
    Phoenix utiliza Cowboy como su servidor HTTP subyacente, encargándose de gestionar las solicitudes HTTP y WebSockets de las aplicaciones web desarrolladas en Elixir.

    Relación entre Phoenix Channels y Cowboy en WebSockets:
    Phoenix Channels emplea Cowboy para gestionar las conexiones WebSocket, permitiendo la comunicación en tiempo real entre el servidor y los clientes de manera eficiente.

Desafíos y Consideraciones:

    Desafíos al aprender Cowboy para nuevos desarrolladores:
    Los principales desafíos incluyen la comprensión del modelo de concurrencia de Erlang, la estructura de Cowboy, y el manejo eficiente de conexiones en aplicaciones distribuidas.

    Tolerancia a fallos de Erlang en aplicaciones con Cowboy:
    Erlang permite construir aplicaciones tolerantes a fallos mediante supervisores que reinician procesos fallidos, lo que garantiza alta disponibilidad y resiliencia en sistemas distribuidos con Cowboy.
## ASCIINEMA
AWS
[![asciicast](https://asciinema.org/a/aXdJui48KoHXL9fkV8CVL7kAK.svg)](https://asciinema.org/a/aXdJui48KoHXL9fkV8CVL7kAK)
CURL
[![asciicast](https://asciinema.org/a/gT0Ho4AkzkpPouWnOjRfzYNCn.svg)](https://asciinema.org/a/gT0Ho4AkzkpPouWnOjRfzYNCn)
![captura](https://github.com/user-attachments/assets/8825ed8a-4e21-4e1a-98e1-99c88b3dacbf)
