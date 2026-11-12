# Lost at SQL

Soluciones y apuntes de una serie de retos SQL con contexto narrativo. Los ejercicios trabajan consultas progresivas sobre tablas de una base de datos ficticia.

## Contenido

- Consultas `SELECT` y proyección de columnas.
- Filtrado de registros.
- Ordenación y agrupación.
- Funciones de agregación.
- Recuentos por ubicación y estado.
- Consultas de dificultad progresiva.

## Estructura

Los archivos `sql/lasql_01.sql` a `sql/lasql_08.sql` contienen las soluciones numeradas de los retos.

## Ejecución

Ejecuta cada consulta en el entorno SQL compatible con el esquema del reto. El repositorio contiene las consultas, no la base de datos completa.

## Tecnologías

- SQL
- Consultas relacionales
- Filtrado y agrupación
- Funciones de agregación

## Project showcase

[Open the GitHub Pages showcase](https://tzayadet.github.io/SQL-Lost-at-SQL/) · [Showcase source](docs/index.html)

The page is an index of the SQL solutions; it does not run a database engine. To publish it, select **Settings → Pages → Build and deployment → Source → GitHub Actions** and set the repository Actions variable `ENABLE_PAGES=true` under **Settings → Secrets and variables → Actions → Variables**. The workflow remains skipped until that variable is enabled.
