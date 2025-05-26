# Diseño de Prototipos de Alta Fidelidad con ChatGPT usando SB Admin 2

## 🎯 Objetivo
Aprender a generar prototipos funcionales de interfaces web a partir de criterios de aceptación de historias de usuario, utilizando **ChatGPT** como asistente de desarrollo y el template **SB Admin 2** con tecnologías web: **HTML**, **CSS** y **JavaScript**.

---

## 🧰 Herramientas y Tecnologías

- [x] HTML5
- [x] CSS3
- [x] JavaScript
- [x] Bootstrap 4
- [x] SB Admin 2 Template (https://startbootstrap.com/theme/sb-admin-2)
- [x] ChatGPT (como generador de código y apoyo en validaciones)

---

## 🗂️ Mapa del Sitio (Site Map)

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

Prompt 1:
```plaintext
Usare SB Admin 2 como template, quiero generar prototipos a partir de requerimientos de aceptación de historias de usuario. Cuando recibas los criterios genera el contenido.
```

Prompt 2:
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
```

Prompt 3:
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
```

Elabora los prototipos de las historias de usuario en base a sus criterios de aceptacion.
- Citerios de aceptacion HU1: Administracion de clientes
- Citerios de aceptacion HU2: Registro de cliente

