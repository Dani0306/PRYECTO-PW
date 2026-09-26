# Classly

Espacio de estudio con inteligencia artificial para estudiantes universitarios: organiza tus clases con su horario, convierte tus apuntes en resúmenes, quizzes y diagramas, y ve todas tus entregas en un calendario.

Proyecto del curso **Programación Web (IF2003), grupo 603**.

## Integrantes

| Nombre         | Usuario de GitHub          |
| -------------- | -------------------------- |
| [Integrante 1] | Daniel Andres Colorado     |
| [Integrante 2] | Juan Jose Hernandez Vargas |

## Documentos del proyecto

- **[Definición del proyecto](docs/definicion.md)**: las 13 secciones, el historial de cambios, las referencias y la declaración de uso de IA. Es la fuente de verdad del proyecto.
- **[Mockup](docs/mockup/)**: una imagen por pantalla (`01`–`14`) y el recorrido entre pantallas por rol (`00-recorrido.png`).
- **[Presentación](docs/presentacion/)**: diapositivas de la sustentación, con una parte no técnica y una parte técnica.
- **[Modelo de datos](docs/diagramas/modelo-datos.png)**: diagrama de entidades y relaciones.

## Estructura del repositorio

```
README.md                     nombre del proyecto, integrantes y enlaces
docs/definicion.md            documento de definición (13 secciones)
docs/mockup/                  una imagen por pantalla y el recorrido
docs/mockup/fuente/           HTML y CSS del mockup, y el script que genera las imágenes
docs/diagramas/               diagrama del modelo de datos
docs/presentacion/            diapositivas de la sustentación (PPTX)
```

## Forma de trabajo en Git

- Cada integrante hace commits propios, con mensajes que digan qué se hizo (por ejemplo, `definicion: agrega RNF de seguridad`).
- Los cambios entran por Pull Request y **nadie fusiona su propio Pull Request**: lo revisa y lo fusiona otro integrante.
- Todo cambio a la definición después de la sustentación se registra en el [historial de cambios](docs/definicion.md#historial-de-cambios).
- Los nombres de archivo van sin tildes, sin eñe y sin espacios.

```bash
cd docs/mockup/fuente
npm install puppeteer
node render.js
```

Para ver una pantalla en el navegador, abre `docs/mockup/fuente/mockup.html` (muestra un índice con todas). Todos los datos del mockup son ficticios.
