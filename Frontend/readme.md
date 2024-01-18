# Frontend changelog

Las fechas corresponden a fechas de despliegue a producción. Branch: Main.

## 27/12/2023 --> acomodar fecha pull request y despliegue

#### Arreglos

- Se añade nueva opción de excel para gestionar inmuebles, principalmente para actualizar el estado. Inactivar las inmuebles en este excel, inactivará las facturas asociadas.
- Se permite seleccionar fechas a futuro en filtros de reportes pendientes.

#### Desarrollos

- Se añade frontend de consumption con CRUD básico de consumos
- Se cambia 'Agrupación' por 'Inmueble".
- En el menú de inmueble solo se muestran y se permite la interacción con inmuebles de proyectos activos.
- Se añade funcionalidad para activar/desactivar inmuebles con slider. Por inmueble y slider general por página. Valida si tiene o no área.
- Se añade filtro de activo/inactivo en la vista de inmumebles.
- Se habilita el sorting para la tabla de inmuebles.
- Se añaden opciones para crear y editar agrupaciones de manera singular.
