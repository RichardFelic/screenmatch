# ScreenMatch

ScreenMatch es un proyecto de Java que explora la gestión de películas y series mediante el uso de una API externa (OMDb) y la manipulación de datos manuales. Este proyecto se desarrolló como parte del aprendizaje del lenguaje Java, enfocándose en la creación de un sistema para calcular y recomendar títulos.

## Funcionalidades

- **Calculadora de Tiempo**: Permite sumar la duración de películas y series.
- **Clasificación**: Implementa una interfaz para obtener la clasificación de los títulos.
- **Filtro de Recomendación**: Filtra y sugiere títulos según su clasificación.
- **Manejo de Excepciones**: Incluye manejo de errores relacionados con la conversión de duración.
- **Modelos**: Define clases para representar películas, series y episodios, incluyendo sus atributos y métodos relevantes.

## Estructura del Proyecto

- **Calculos**: Contiene clases como `CalculadoraDeTiempo`, `FiltroRecomendacion` y la interfaz `Clasificacion`.
- **Modelos**: Define las clases `Titulo`, `Pelicula`, `Serie`, `Episodio` y `TituloOmdb`.
- **Principal**: Clase principal que ejecuta el programa y maneja las interacciones con los usuarios.

## Ejemplo de Uso

El programa permite crear instancias de `Pelicula` y `Serie`, evaluar su rendimiento y mostrar información detallada sobre ellas. También puede leer datos de archivos y generar recomendaciones basadas en la popularidad de los títulos.

## Requisitos

- JDK 11 o superior
- Dependencias de Google [Gson 2.11.0](https://repo1.maven.org/maven2/com/google/code/gson/gson/2.11.0/gson-2.11.0.jar) para manejar JSON (si se usa la API).

## Instalación

1. Clona el repositorio:
   ```bash
   git clone <url-del-repositorio>```

## Contribuciones

Las contribuciones son bienvenidas. Siéntete libre de hacer un fork del proyecto y enviar un pull request.
