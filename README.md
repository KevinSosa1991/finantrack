# FinanTrack

## Descripción
FinanTrack es una aplicación web para el control personal de ingresos y gastos. Muestra un dashboard con el saldo disponible, permite registrar y eliminar movimientos, filtrarlos, ordenarlos por fecha y ver cómo se distribuyen los gastos por categoría.

## Objetivo
Ofrecer un proyecto pequeño, estable y fácil de explicar, construido sin frameworks ni dependencias externas, que sirva como base para practicar el empaquetado, el versionamiento y el despliegue de aplicaciones web.

## Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript vanilla
- LocalStorage del navegador

## Funcionalidades principales
- Registro de ingresos y gastos con validación de campos.
- Dashboard con saldo, total de ingresos, total de gastos y número de movimientos.
- Resumen del mes actual.
- Lista de movimientos con filtros (Todos, Ingresos, Gastos) y orden por fecha.
- Eliminación con confirmación dentro de la interfaz.
- Distribución de gastos por categoría con barras hechas en HTML/CSS.
- Los datos se conservan en el navegador mediante LocalStorage.

## Estructura básica de carpetas
```
finantrack/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── img/
│   └── logo.png
├── README.md
└── .gitignore
```

## Cómo ejecutarlo localmente
La aplicación debe abrirse desde un servidor web local, no con doble clic sobre el archivo.

1. Abre una terminal dentro de la carpeta `finantrack/`.
2. Inicia un servidor local con Python:
   ```
   python3 -m http.server 8080
   ```
3. Abre el navegador en `http://localhost:8080`.
4. Para detener el servidor, presiona `Ctrl + C` en la terminal.
