SIN USAR Express Generator

# Heroes
Objetivo
Para la construcción de este pequeño sitio web se espera contar con la posibilidad de
acceso a las siguientes URL's:
● /
● /heroes
● /heroes/detalle/id - (id = número, obligatorio)
● /heroes/bio/id/ok - (id = número, obligatorio / ok = string, optativo)
● /creditos

Refactorizando su código
Toda persona que se estime buena para la programación siempre va por más. Es por
ello que en este punto y ya teniendo TODO lo anterior hecho y funcionando a la
perfección. Les sugerimos darle una "vueltita de rosca" a lo hecho y refactorizar su
aplicación para que la misma tenga:
1. un sistema de ruteo modularizado
2. un sistema de controladores que administren las peticiones del cliente
Para ello, la estructura de directorios que recomendamos seguir será la siguiente:
├── data
│ └── heroes.json
├── controllers
│ ├── heroesController.js
│ └── mainController.js
├── routes
│ ├── heroes.js
│ └── main.js
├── app.js
└── package.json

