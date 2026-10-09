[README.md](https://github.com/user-attachments/files/33257932/README.md)
# Presupuesto mensual LLYASA

- `index.html`: la aplicación (no cambia cada mes).
- `datos.js`: ventas, ajustes y parámetros, **cifrados con contraseña**. Es lo único que cambia.

## Modo edición (solo para quien administra)
El sitio abre en **solo lectura** para el equipo: sin captura, sin ajustes y sin publicar.
Para editar, haz **tres clics seguidos en el título** "Presupuesto mensual por ejecutivo". Aparecen los botones y el navegador
se queda en modo edición. Tres clics más lo desactivan. También funciona abriendo el sitio con `?editar` al final de la dirección.

## Actualización mensual
1. En modo edición, entra a **Captura de ventas**, pega las ventas y presiona **Aplicar captura**.
2. En **Publicar para todos** presiona **Publicar ahora** (necesita el token de GitHub guardado en tu navegador).
3. En uno o dos minutos el sitio se actualiza (recarga con Ctrl+F5).

## Seguridad
Ocultar los botones es solo orden, no seguridad. Lo que impide que otros cambien los datos publicados es el **token de GitHub**
(solo está en tu navegador) y los permisos del repositorio. Quien agregue `?editar` solo verá los botones; sus cambios no llegan a nadie.

Nunca subas un `datos.js` sin cifrar (el que empieza con `window.DATOS=`).
