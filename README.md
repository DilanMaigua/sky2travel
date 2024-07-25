# Sky2Travel Chatbot

Este programa es un chatbot creado en Python utilizando Google Colab, que te ayudará a planificar tus viajes, identificando ciudades, aerolíneas y países mencionados en tu mensaje.

## Requisitos

Para ejecutar este programa, necesitas los siguientes archivos CSV:
- `aerolineas.csv`: Contiene una lista de las 20 aerolíneas más importantes del mundo.
- `ciudades.csv`: Contiene una lista de ciudades y paises con aeropuertos importantes en el mundo.

## Configuración y Ejecución

1. **Abrir el archivo en Google Colab**: Sube los archivos `aerolineas.csv`, `ciudades.csv` a los archivos de Google Colab.
2. **Ejecutar el programa**: Una vez cargados los archivos CSV, ejecuta todas las celdas en el notebook de Google Colab.
3. **Interacción con el chatbot**: Después de ejecutar las celdas, interactúa con el chatbot escribiendo tu mensaje en la caja de texto y presionando el botón "Enviar".

## Uso del Programa

Después de cargar y ejecutar el programa en Google Colab, puedes interactuar con el chatbot escribiendo mensajes relacionados con viajes. El chatbot procesará tu mensaje y extraerá información relevante como la ciudad de origen, ciudad de destino, aerolínea, fecha y cantidad de billetes.

## Salida Esperada

El chatbot proporcionará una respuesta basada en la información que encuentre en tu mensaje. Por ejemplo:

"Perfecto. Comienzo la búsqueda de tu viaje de Madrid a París con Iberia."
"Fecha: 15 de agosto."
"Cantidad: 2 billetes."
Además, el chatbot mostrará la información extraída en formato JSON.

## Nota

Si el mensaje no contiene información suficiente para determinar el origen y destino, el chatbot te pedirá que intentes de nuevo.
