# Formulario HTML5 responsive

## Validación

- Todos los campos son obligatorios menos el de información adicional
- Se deben validar los campos de la siguiente manera:
  - La fecha debe ser válida
  - El correo electrónico debe ser válido
  - El sitio web debe ser válido
  - El DNI debe tener una longitud de 9 caracteres
  - El código postal debe tener una longitud de 5 caracteres
  - El teléfono debe tener una longitud de 9 números
    
## Diseño accesible

- Todos los campos deben tener una etiqueta `label`
- Se deben utilizar `fieldsets` para agrupar los campos relacionados

## Diseño responsivo

- Se debe realizar un diseño *mobile first*
- Diseño móvil:
  - Las etiquetas deben estar ocultas (excepto los campos `radio` y `checkbox`)
  - Los campos de formulario deben ocupar el ancho completo de la pantalla
- Diseño de tablet:
  - Las etiquetas deben mostrarse encima de los campos
  - El formulario debe ocupar un 80% de la pantalla y aparecer centrado
- Diseño de pantallas grandes:
  - El formulario debe aparecer *dividido en dos columnas*.
  - El botón de envío debe aparecer *centrado* debajo de las dos columnas.
  - Las etiquetas deben aparecer alineadas a la derecha y mostrarse a la izquierda de los campos
  - El formulario debe tener un ancho máximo de 1024px
