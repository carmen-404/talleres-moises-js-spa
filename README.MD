<p align="center">
  <img src="img/logo/logo.webp" alt="Logo de Talleres Moises" width="420">
</p>

<h1 align="center">Talleres Moises · Aplicación PHP</h1>

<p align="center">
  <em>Mecánica · Reparación | Profesionalidad y confianza</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Bootstrap_5-7952B3?logo=bootstrap&logoColor=white" alt="Bootstrap 5">
  <img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL">
</p>

---

## Sobre el proyecto

Proyecto de la asignatura **Desarrollo de Interfaces (2º DAM)**, segunda parte.
Temática: **Taller Mecánico de Vehículos**.

Aplicación web (SPA) para controlar el flujo de reparaciones de los clientes del taller: gestión de clientes, coches, reservas y servicios.

La primera parte (web corporativa estática) está en el repositorio [Talleres-Moises](https://github.com/L3V1XX/Talleres-Moises).

## Enlaces

- 💻 **Repositorio GitHub:** [talleres-moises-js-app](https://github.com/carmen-404/talleres-moises-js-spa)
- 🌐 **Alojamiento web:** [talleres-moises-php-app.free.je](https://talleres-moises-js-spa.free.je)

## Conexión a la base de datos (`config.php`)

| Parámetro | Valor |
| :--- | :--- |
| Servidor | `db` |
| Puerto | `3306` |
| Base de datos | `talleres_moises` |
| Usuario | `root` |
| Password | `test` |

> Los scripts SQL están en la carpeta `sql/`:
> - `backup.sql`: crea la base de datos `talleres_moises`, las tablas, relaciones y datos de la tabla genérica (codigos_postales).
> - `backup_sin_create_database.sql`: igual, pero sin `CREATE DATABASE` (para hostings donde la base de datos ya viene creada).
> - `seed_data.sql`: inserta datos ficticios en todas las tablas para poder hacer pruebas.


## Reparto de responsabilidades

| Alumno | Entidad responsable |
| :--- | :--- |
| Javier Rodríguez | `Cliente` |
| José Manuel Payán | `Coche` |
| Carmen Díaz | `Reserva` |
| Moisés Orozco | `Servicios` |
