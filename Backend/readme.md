# Backend changelog

Las fechas corresponden a fechas de despliegue a producción

## Branch: main

### 27/12/2023 --> acomodar fecha pull request y despliegue

- Se añade backend de consumption con CRUD básico de consumos
- Se añade nueva opción de excel para gestionar agrupaciones, principalmente para actualizar el estado. Inactivar las agrupaciones en este excel, inactivará las facturas asociadas.
- Se eliminan las columnas estado, period_end_date del excel de facturas manejado previamente.
- Se elimina el estado "entregado" de los inmuebles. Solo Activo/inactivo.
- Se cambia 'Agrupación' por 'Inmueble".
