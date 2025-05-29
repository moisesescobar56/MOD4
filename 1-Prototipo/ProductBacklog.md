# Diseño de Prototipos de Alta Fidelidad con ChatGPT

## Objetivo
Aprender a generar prototipos funcionales de interfaces web a partir de criterios de aceptación de historias de usuario, utilizando **ChatGPT** como asistente de desarrollo y el template **SB Admin 2** con tecnologías web: **HTML**, **CSS** y **JavaScript**.

---

## Herramientas y Tecnologías

- [x] HTML5
- [x] CSS3
- [x] JavaScript
- [x] Bootstrap 5
- [x] SB Admin 2 Template (https://startbootstrap.com/theme/sb-admin-2)
- [x] ChatGPT (como generador de código y apoyo en validaciones)

---

## Mapa del Sitio (Site Map)

```plaintext
📌 El Paraisal
├── Venta
│   ├── Registrar → registrar_venta.html
│   ├── Historial → historial_venta.html
│   └── Cliente → cliente.html
│
├── Mantenimiento
│   ├── Producto → producto.html
│   ├── Categoría → categoria.html
│   └── Empleado → empleado.html
│
└── Reportes
    └── Reporte 1 → reporte1.html
```

# Guia de Prompts
### Prompt 1:
```plaintext
Usare SB Admin 2 como template, quiero generar prototipos a partir de requerimientos de aceptación de historias de usuario,  Cuando recibas los criterios genera el contenido genera el contenido desde el container-fluid.
```

### Prompt 2:
```plaintext
Site map:
- index.html
- auth.html
- cliente.html
- registrar_cliente.html
- categoria.html
- registrar_categoria.html
- producto.html
- registrar_producto.html
- empleado.html
- registrar_empleado.html
- historial_venta.html
- registrar_venta.html
- reporte1.html
- reporte2.html
```

### Prompt 3:
```plaintext
Usa la plantilla y genera un menu de navegación en el panel lateral, El Paraisal donde tenga enlaces a:

- Venta
 - Registrar (venta.html)
 - Historial (historial.html)
 - Cliente (cliente.html)
- Mantenimiento
  - Producto (producto.html)
  - Categoría (categoria.html)
  - Empleado (empleado.html)
- Reportes
  - reporte1.html
  - reporte2.html
```
### Generar prototipos
Elabora los prototipos de las historias de usuario en base a sus criterios de aceptacion.
- HU1: Administracion de cliente
```plaintext
Proceso de BUSCAR:
    Agrega un botón de NUEVO que redireccione a la pantalla de registro de cliente.
    Agregar un filtro para buscar Clientes por: Nombre, Apellido o DUI
    La tabla de reporte de clientes solo tendrá las columnas:
        ClienteId
        Nombre
        Apellido
        DUI
        Teléfono
        Correo electrónico
Proceso de EDITAR:
    Agregar un botón de EDITAR en la tabla que sea amarillo.
    Para editar un registro primero se debe dar clic al boton del registro de la tabla.
    Al dar clic en el botón de EDITAR debe redireccionar y mostrar un formulario para editar los datos del Cliente seleccionado y Guardar los cambios en caso de realizar alguno.
Proceso de ELIMINAR:
    Agregar un botón de ELIMINAR en la tabla que sea rojo.
     Para eliminar un registro primero se debe dar clic al boton del registro de la tabla.
    Al dar clic en el botón de ELIMINAR se presentará una ventana de confirmación con el mensaje "¿Está seguro de eliminar el registro seleccionado?" y con dos opciones: Confirmar o Cancelar.
```
- HU2: Registro de cliente
```plaintext
﻿Datos de entrada:
    Nombre (Obligatorio)
    Apellido (Obligatorio)
    Teléfono (Obligatorio), validar formato para teléfono de 8 dígitos.
    DUI (Obligatorio), validar formato para DUI de 9 dígitos.
    Correo electrónico (Obligatorio), validar formato de correo electrónico.
    Dirección de residencia (Obligatorio)
Se debe mostrar un botón para GUARDAR en color azul y otro botón para CANCELAR el proceso que sea rojo que redireccione a la página de administración de cliente. 

Mensajes de salida:
    Al guardar al Cliente se debe mostrar un mensaje de confirmación que se realizó correctamente el proceso.
    En caso de error, se debe mostrar un mensaje que informe el error ocurrido.
```

