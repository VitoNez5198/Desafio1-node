# Veterinaria Js

Esta es una aplicación backend desarrollada en Node.js que registra los datos de atención en una veterinaria.

## Uso

La aplicación admite dos operaciones:

- Registrar: Agrega una nueva cita de una atención veterinaria que debe incluir:
  - Nombre del animal
  - Edad
  - Tipo de animal
  - Color del animal
  - Enfermedad

  Ejemplo: `node index.js registrar Trevor "4 años" gato gris "dolor de estomago"`

- Leer: Muestra por consola todas las citas registradas.

  Ejemplo: `node index.js leer`

- Adicionalmente, puedes utilizar la operación "limpiar" para eliminar todas las citas registradas:

  Ejemplo: `node index.js limpiar`

## Archivos

- `index.js`: Archivo principal que se debe ejecutar para interactuar con la aplicación.
- `operaciones.js`: Archivo que contiene las funciones para registrar, leer y limpiar citas.
- `citas.json`: Archivo JSON que almacena las citas registradas.

