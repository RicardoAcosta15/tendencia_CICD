[![Deployment Pipeline](https://github.com/RicardoAcosta15/tendencia_CICD/actions/workflows/pipeline.yml/badge.svg)](https://github.com/RicardoAcosta15/tendencia_CICD/actions/workflows/pipeline.yml)

# tendencia_CICD

Repo para la tarea de tendencias de CI/CD<br>

Definir un flujo de integración contínua para el proyecto escogido. Los pasos imprescindibles a considerar
son:<br>
  i. Descargar el código (utilizamos uses: actions/checkout@v3).<br>
  ii. Instalación de dependencias (de haber) (utilizamos npm ci --no-audit --no-fund --no-optional).<br>
  iii. Compilación o transpilación del código (utilizamos npm run build).<br>
  iv. Análisis de estilo y/o sintático (lint) (utilizamos npm run eslint).<br>
  v. Corrida de pruebas unitarias. De no haber pruebas unitarias es requerido que creen al menos una
prueba unitaria. (utilizamos npm test)

## Commandos

Comience corriendo `npm install` dentro de la carpeta del proyecto

`npm start` para correr el webpack dev server
`npm test` para correr los tests
`npm run eslint` para correr eslint
`npm run build` para hacer un production build
