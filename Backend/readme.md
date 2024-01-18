# Backend changelog

Las fechas corresponden a fechas de despliegue a producción. Branch: Main.

## 27/12/2023 --> acomodar fecha pull request y despliegue

#### Arreglos

- Se añade nueva opción de excel para gestionar agrupaciones, principalmente para actualizar el estado. Inactivar las agrupaciones en este excel, inactivará las facturas asociadas.
- Se añade validación para que al actualizar la fecha de pago se considere además del invoiceNumber el código de la compañía. Se introduce esta función dentro de un sql transaction.

#### Desarrollos

- Se añade backend de consumption con CRUD básico de consumos
- Se eliminan las columnas estado, period_end_date del excel de facturas manejado previamente.
- Se elimina el estado "entregado" de los inmuebles. Solo Activo/inactivo.
- Se cambia 'Agrupación' por 'Inmueble".
- Si el proyecto está inactivo, no se exporta ni inmuebles ni csg en excel. Tampoco se recibe en excel de creación. Dado que la idea es que se son inactivos ya saldrían del sistema todos los inmuebles asociados.
- Se añade endpoint para activar/inactivar inmuebles desde el frontend.
- Se añade inactivación de Inmuebles al inactivar Proyectos. Al activar proyectos no afecta el estado de los inmuebles.
- Se añaden servicios para crear y editar agrupaciones de manera singular.
