# FinanTrack

Aplicación web para el control personal de ingresos y gastos, desarrollada con HTML5, CSS3 y JavaScript vanilla.

## 1. Descripción del proyecto

FinanTrack es una aplicación web que permite registrar y consultar ingresos y gastos personales. Presenta un dashboard con el saldo disponible, los totales de ingresos y gastos, el número de movimientos registrados y un resumen de los gastos por categoría.

La aplicación utiliza LocalStorage para conservar los movimientos en el navegador, sin requerir una base de datos ni un servidor de aplicaciones.

## 2. Objetivo

Desarrollar una aplicación web pequeña, estable y fácil de mantener que permita practicar los procesos de optimización, empaquetado, versionado y despliegue de aplicaciones web en un servidor Apache.

## 3. Tecnologías utilizadas

- HTML5: estructura y contenido de la aplicación.
- CSS3: diseño visual y adaptación a diferentes tamaños de pantalla.
- JavaScript vanilla: lógica, validaciones y actualización de la interfaz.
- LocalStorage: almacenamiento local de los movimientos.
- Git: control de versiones.
- GitHub: alojamiento remoto del repositorio.
- Apache: servidor web previsto para el despliegue.

## 4. Funcionalidades principales

- Registro de ingresos y gastos con validación de campos.
- Dashboard con saldo, total de ingresos, total de gastos y número de movimientos.
- Resumen del mes actual.
- Lista de movimientos con filtros por tipo y ordenamiento por fecha.
- Eliminación de movimientos con confirmación.
- Distribución de gastos por categoría mediante barras creadas con HTML y CSS.
- Persistencia de datos en el navegador mediante LocalStorage.

## 5. Estructura del proyecto

```text
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

## 6. Optimización y empaquetado

Para preparar la aplicación para su distribución, se realizaron las siguientes acciones:

1. Se organizaron los archivos HTML, CSS, JavaScript e imagen en directorios separados.
2. Se minificó la hoja de estilos CSS para reducir su tamaño.
3. Se minificó el archivo JavaScript para reducir su tamaño.
4. Se comprobó que la aplicación continuara funcionando después de la optimización.
5. Se creó un archivo ZIP con la estructura final del proyecto.

La optimización se realizó sin incorporar frameworks ni dependencias externas al funcionamiento de la aplicación.

## 7. Control de versiones

El proyecto utiliza Git para registrar los cambios y conservar un historial de versiones.

El repositorio remoto está alojado en GitHub:

https://github.com/KevinSosa1991/finantrack

La versión inicial optimizada se registró con el siguiente commit:

```text
feat: version inicial optimizada de FinanTrack
```

La rama principal utilizada es `main`.

Para consultar el historial de versiones se puede ejecutar:

```bash
git log --oneline
```

Para revisar el estado actual del repositorio:

```bash
git status
```

## 8. Ejecución local

Para probar la aplicación en Windows con Python instalado:

1. Abre una terminal dentro de la carpeta `finantrack/`.
2. Ejecuta el siguiente comando:

   ```bash
   py -m http.server 8080
   ```

3. Abre el navegador y visita:

   http://localhost:8080

4. Para detener el servidor, presiona `Ctrl + C` en la terminal.

Este servidor se utiliza para realizar pruebas locales y no sustituye la configuración del servidor Apache prevista para el despliegue.

## 9. Despliegue

El despliegue del proyecto se realizará mediante un servidor web Apache.

La configuración prevista permitirá acceder a la aplicación desde una dirección local con una ruta específica, de acuerdo con los requisitos de la actividad académica.

Los detalles de la configuración del servidor y las pruebas de acceso se documentarán una vez completado el despliegue.

## 10. Autoría y propósito académico

FinanTrack es un proyecto académico desarrollado para practicar la preparación, optimización, empaquetado, control de versiones y despliegue de aplicaciones web.