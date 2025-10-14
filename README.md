Parcial Programación III – UTN FRA 2025

Alumno/a: Evelyn Eduards
Materia: Programación III
Año: 2025
Archivo principal: pintureria.html
API: https://utnfra-api-pinturas.onrender.com/pinturas

Objetivo

Desarrollar una aplicación web tipo CRUD que permita listar, agregar, modificar y eliminar pinturas mediante una API REST, aplicando validaciones, diseño responsive y mejoras de UX/UI con Bootstrap 5 y JavaScript puro.

Funcionalidades principales
 Parte 1 – Listado y Alta

Obtiene el listado de pinturas con GET /pinturas.

Muestra una tabla con columnas: ID, Marca, Precio, Color, Cantidad.

Permite agregar nuevas pinturas con POST /pinturas.

Parte 2 – Modificación y Eliminación

Botones con íconos de editar y eliminar por fila.

Carga los datos seleccionados en el formulario para editar (PUT /pinturas/:id).

Elimina registros con confirmación (DELETE /pinturas/:id).

Muestra alertas Bootstrap de éxito o error.

 Parte 3 – Validaciones

Marca, precio y cantidad obligatorios.

Precio entre 50 y 500; cantidad entre 1 y 400.

Se usan clases is-invalid, is-valid y invalid-feedback.

Parte 4 – UX Mejorado

Spinner de carga mientras se comunica con la API.

Filtro por marca.

Cálculo de precio promedio con reduce() y alert().

Diseño responsive y visual atractivo.

 Parte 5 – UI Avanzada

Navbar fija con logo UTN y botón modo oscuro/claro.

Tabs para separar Formulario, Listado y Estadísticas.

Estilos modernos, íconos y tipografía legible.

 Parte 6 – Estadísticas y Exportación

Muestra total de pinturas, marca más común, mayor precio y promedios.

Permite exportar el listado a CSV.

Implementa modo oscuro/claro con persistencia en localStorage.

 Tecnologías usadas

HTML5, CSS3, Bootstrap 5, JavaScript 

API REST pública UTN FRA

 Conclusión

La app implementa un CRUD completo, validaciones, manejo de errores y mejoras visuales que garantizan una buena experiencia de usuario. Cumple con todos los puntos del examen y sigue las buenas prácticas de desarrollo frontend.
