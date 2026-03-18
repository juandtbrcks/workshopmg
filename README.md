# workshopmg


## Ejercicio.

El objetivo de este ejercicio es realizar la transición de datos desde su estado de integración (capa Silver) hacia su preparación final para el negocio (capa Gold). Durante el ejercicio, simularemos el procesamiento, depuración y enriquecimiento de la información, garantizando su calidad estructural. Una vez consolidada la capa Gold y asegurada mediante Unity Catalog, demostraremos su valor tangible al consumirla a través de dos frentes: la creación de un Dashboard analítico para el monitoreo de métricas clave, y la implementación de un 'Genie Space', el cual empoderará a los usuarios a interactuar con los datos organizacionales utilizando lenguaje natural fluido y sin necesidad de código.

## Actividades

1. Carga de archivos de datos sinteticos de usuarios y suscripciones
2. Navegación en unity catalog de nuevas tablas generadas
3. Agregar metadata adicional , puede ser descripción de campos, etiquetas 
4. Crear un pipeline oro (con apoyo de Genie code)
5. Crear dashboard (con apoyo de Genie code)
6. Creación de un genie code
7. Asignar instrucciones al genie space (con apoyo de Genie code)



## Prompts de ejemplo para Genie Code

### Creación de pipeline oro

A partir de los datos existentes de usuarios y suscripciones en capa plata en el esquema [mi esquema], genera un pipeline que procese los datos hacia la capa oro , puedes proponer agregar nuevas métricas que le harían sentido a un analista de negocio, agrega las expectativas que consideres utiles para evitar problemas de calidad de datos en capa oro. utiliza SQL


### Creación de dashboard

Genera un dashboard ejecutivo que permita analizar el detalle de las suscripciones y sus respectivos usuarios, considera aspectos de ingresos, cancelaciones, segmentación por tipo de usuarios, entre otros indicadores que te parezcan relevantes


### Creación de un Genie Code

Tengo un Genie Space que utiliza la capa Gold de las suscripciones, genera las instrucciones (en español)  para que sea capaz de responder a usuarios de negocio de manera concisa desde un punto de vista ejecutivo. Dame también preguntas de ejemplo.
