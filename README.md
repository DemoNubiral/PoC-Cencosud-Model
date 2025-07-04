# PoC-Cencosud-Model
Repositorio en donde se centralizó lo trabajado para Cencosud

## Arquitectura PoC 
![arquitectura-poc](https://.png)

## Configuración inicial

Abrir un Terminal

Ir a la carpeta donde guardas tus proyectos. Ejemplo:

`cd C:\Nubiral\Proyectos\` 

Clonar repositorio (crea el directorio PoC-Cencosud-Model): 

`git clone git@github.com:matiasparientenubiral/prisma-poc-teradata.git`

Ir al directorio: `cd prisma-poc-teradata`

Ir a la rama develop: `git checkout develop`

## Buenas prácticas para mensajes de commit

- Fix: Correcciones
- Feature: Nuevas funcionalidades
- Refactor: Mejoras de código
- Docs: Documentación
- Test: Pruebas

Ejemplos:

`git commit -m "fix: Corregir error en la conversión de fechas"`

`git commit -m "Feature: añadir filtros avanzados en búsqueda"`

`git commit -m "Refactor: optimizar consultas de base de datos"`

`git commit -m "Docs: actualizar instrucciones de instalación"`

`git commit -m "Test: añadir tests unitarios para módulo de autenticación"`

## Estructura de carpetas


## Descripción de carpetas y archivos
- [caso-analitico-payway/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/caso-analitico-payway) : Contiene scripts y notebooks del caso analítico relacionado a Payway.

- [caso-analitico-prisma/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/caso-analitico-prisma): Contiene el desarrollo del caso analítico de Prisma.

- [caso-operativo/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/caso-operativo): Lógica y automatización para el caso operativo.

- [docs/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/docs): Documentación general del proyecto.

- [lambda-scripts/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/lambda-scripts): Código fuente de las funciones Lambda utilizadas.

- [step-functions-scripts/](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/caso-analitico-payway): Definiciones y lógica de AWS Step Functions.

- [etl_template.ipynb](https://github.com/matiasparientenubiral/prisma-poc-teradata/tree/develop/caso-analitico-payway): Plantilla base de notebook para procesos ETL.
