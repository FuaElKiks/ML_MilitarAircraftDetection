# ML_MilitarAircraftDetection
Modelo de redes neuronales que detecta mas de 81 tipos de naves militares

Public Data: https://www.kaggle.com/code/abdallahwagih/military-aircraft-detection-efficientnetb3-93

Usando dos modelos, conseguimos una predicción del tipo de nave que queramos con el porcentaje de seguridad. Los pesos de los modelos están guardados en h.5
Para que el modelo funcione, es necesario descargar y tener en el mismo directorio que el notebook la carpeta "crop" con las diferentes carpetas de labels con sus imagenes tal y como se puede descargar del dataset de kaggle.

Usamos un pequeño for para que se usen dos modelos (iban a ser mas pero por tiempo y capacidad tuvieron que ser dos), que son entrenados en la detección de 81 tipos diferentes de aviones militares.

Resultado final: Una simple aplicación donde puedes arrastrar una imagen y te devuelve el tipo de avión predicho con su porcentaje de seguridad por cada uno de los dos modelos.
### Importante:
Los modelos .h5, debido a su peso no han podido ser subidos a github (525mb), pero compilando el notebook se guardan automaticamente
Nota: Posibilidad de implementar efficientnet desde el mismo codigo descomentando.
