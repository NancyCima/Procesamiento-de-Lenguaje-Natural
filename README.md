# 🌴 Recomendador de Actividades Recreativas 🌴

Este es un proyecto de recomendación basado en el estado de ánimo y preferencias del usuario. La aplicación ofrece sugerencias personalizadas de películas, libros y juegos que pueden ser ideales para disfrutar durante el tiempo libre.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Descripción

El **Recomendador de Actividades Recreativas** es una aplicación que interactúa con el usuario para ofrecerle recomendaciones de entretenimiento (películas, libros, juegos, etc.). El sistema utiliza un clasificador de emociones para determinar el estado de ánimo del usuario y combinarlo con sus preferencias. Las recomendaciones se muestran en un formato fácil de leer, con cada actividad detallada en líneas separadas para mayor claridad.

## Características

- Clasificación de emociones a partir de texto ingresado por el usuario.
- Recomendaciones personalizadas de acuerdo con el estado de ánimo y las preferencias de actividad.
- Soporte para múltiples categorías de entretenimiento (películas, libros, juegos).
- Formato de salida legible con detalles específicos sobre cada recomendación.

## Uso

El programa te guiará con las siguientes opciones:

1. **Ingresar tu estado de ánimo**: Describe cómo te sientes.
2. **Ingresar tus preferencias**: Indica, por ejemplo, si te gustaría ver una comedia o leer un libro de un autor especifico.

La aplicación procesará esta información y te dará recomendaciones personalizadas en las distintas categorías.


## Estructura del Proyecto

- `Recomendador`: Script principal para ejecutar la aplicación. Contiene la lógica para clasificar el estado de ánimo del usuario y para generar recomendaciones basadas en el estado de ánimo y las preferencias del usuario.
- `Web_Scraping_+_Creacion_Dataset.ipynb`:  Script con la lógica para generar el dataset de libros mediante web scraping y para la creación del dataset utilizado en el entrenamiento del modelo de clasificación de sentimientos.
- `data/`: Carpeta donde se almacenan los datos de actividades (películas, libros, juegos).
- `Informe - Trabajo Práctico N°1 - NLP.pdf`: Informe detallado de cómo se llevo a cabo el proyecto y qué decisiones se tomaron.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b feature-tu-mejora`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva característica'`).
4. Sube tus cambios a tu repositorio (`git push origin feature-tu-mejora`).
5. Crea un Pull Request en GitHub.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes consultar el archivo `LICENSE` para más detalles.

---

¡Gracias por usar el Recomendador de Actividades Recreativas!
```