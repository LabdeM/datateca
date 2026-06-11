## datateca
Aquí encontrarás las bases de datos utilizadas en distintas investigaciones realizadas por miembrxs de la comunidad de la FLACSO México. Cada carpeta contiene los datasets correspondientes a un proyecto de investigación, así como su respectivo libro de códigos.

## ¿Cómo contribuir con bases de datos?

Si quieres que agreguemos tu base de datos al repositorio, asegúrate de que cumpla con los siguientes requisitos:

### Formato del archivo
- Formato .csv (UTF-8)
- Primera fila como encabezado
- Sin filas ni columnas vacías al inicio
- Sin celdas combinadas
- Sin fórmulas activas (solo valores)

### Estructura de los datos
- Una observación por fila
- Nombres de variables en `snake_case`
- Valores faltantes estandarizados (usar `NA` o celda vacía de forma consistente)

### Documentación mínima
Incluye un libro de códigos con al menos:
- Nombre de las variables
- Descripción
- Tipo de datos (numérico, categórico, fecha, etcétera)
- Categorías o unidades, según corresponda

También indica la **fuente o procedencia** de los datos, la **fecha de recolección o corte temporal**, y si tienen alguna **licencia o restricción de uso**.

En la carpeta `plantillas_LabdeM` encontrarás la plantilla `.tex` y el archivo `.Rmd` de ejemplo para elaborar tu libro de códigos.

### ¿Cómo enviarla?
Escríbenos a [labdem@flacso.edu.mx] y nos pondremos en contacto contigo para coordinar la revisión.

