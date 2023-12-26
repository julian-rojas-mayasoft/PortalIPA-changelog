# Backend changelog

Las fechas corresponden a fechas de despliegue a producción. Branch: Main.

## 27/12/2023 --> acomodar fecha pull request y despliegue

#### Arreglos

- Se añade nueva opción de excel para gestionar agrupaciones, principalmente para actualizar el estado. Inactivar las agrupaciones en este excel, inactivará las facturas asociadas.

#### Desarrollos

- Se añade backend de consumption con CRUD básico de consumos
- Se eliminan las columnas estado, period_end_date del excel de facturas manejado previamente.
- Se elimina el estado "entregado" de los inmuebles. Solo Activo/inactivo.
- Se cambia 'Agrupación' por 'Inmueble".
