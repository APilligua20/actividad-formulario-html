Este repositorio contiene un formulario web desarrollado **únicamente con HTML puro** (sin CSS ni JavaScript), como parte de una actividad académica.
El formulario permite registrar estudiantes interesados en un taller de desarrollo web, recopilando información personal, académica,
preferencias del taller,disponibilidad y comentarios adicionales.

## Propósito
Demostrar el uso de diversos elementos de formulario HTML, atributos de validación nativos y una estructura semántica correcta, cumpliendo con los requisitos especificados en la actividad.

## Características del formulario
- **Campos obligatorios** marcados con `required`.
- **Validaciones HTML5** como `minlength`, `maxlength`, `min`, `max`, `step`, `placeholder`, etc.
- **Tipos de `<input>` incluidos**:  
  `text`, `email`, `tel`, `number`, `date`, `time`, `url`, `radio`, `checkbox`, `file`, `color`, `range`.
- **Elementos específicos**:  
  `<select>` y `<option>` para niveles académicos y jornada; `<textarea>` para comentarios; `<button>` de enviar y limpiar.
- **Organización**:  
  Uso de `<fieldset>` y `<legend>` para agrupar las secciones (Datos personales, académicos, preferencias, disponibilidad, información adicional).
- **Sin dependencias externas** – solo HTML, funciona en cualquier navegador moderno.

## Validaciones incluidas
- **Nombres**: mínimo 3 caracteres, máximo 80.
- **Edad**: entre 15 y 80 años.
- **Teléfono**: patrón de 10 dígitos (opcional pero validado si se ingresa).
- **Correo electrónico**: formato estándar con `type="email"`.
- **Nivel académico**: selección obligatoria.
- **Modalidad y conocimiento previo**: radios obligatorios.
- **Rango de motivación**: valor numérico de 1 a 10.

## 🧪 Prueba el formulario
Puedes probar el envío. Los botones “Enviar inscripción” y “Limpiar formulario” funcionan según el comportamiento nativo del navegador.

## Autor
Andy Pilligua
Repositorio creado para la actividad “Taller de Desarrollo Web”.

## 🔗 Enlace al repositorio
https://github.com/APilligua20/actividad-formulario-html.git
