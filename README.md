# Presupuesto mensual LLYASA

- `index.html`: la aplicación (no cambia cada mes).
- `datos.js`: ventas, ajustes y parámetros, **cifrados con contraseña**. Es lo único que cambia.

## Actualización mensual
1. Abre el sitio, escribe la contraseña, entra a **Captura de ventas**, pega las ventas y presiona **Aplicar captura**.
2. En **Publicar para todos** presiona **Descargar datos.js** (sale cifrado con la contraseña actual).
3. En GitHub: **Add file → Upload files**, arrastra `datos.js` (reemplaza al anterior) y **Commit changes**.
4. GitHub Pages se actualiza solo en un par de minutos.

## Cambiar la contraseña
Antes de descargar, escribe la contraseña nueva (mínimo 10 caracteres) en el campo de Publicar. Sube el `datos.js` resultante y avisa la nueva clave al equipo.

## Importante
- Nunca subas un `datos.js` sin cifrar (el que empieza con `window.DATOS=`). El cifrado lo genera siempre el dashboard.
- Si se filtra la contraseña, cámbiala y vuelve a publicar; las versiones anteriores del archivo siguen en el historial del repositorio y se abrirían con la contraseña vieja.
