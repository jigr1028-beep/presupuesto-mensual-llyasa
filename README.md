[README.md](https://github.com/user-attachments/files/33127719/README.md)
# Presupuesto mensual LLYASA

- `index.html`: la aplicación (no cambia cada mes).
- `datos.js`: ventas, ajustes y parámetros, **cifrados con contraseña**. Es lo único que cambia.

## Actualización mensual
1. Abre el sitio, escribe la contraseña, entra a **Captura de ventas**, pega las ventas y presiona **Aplicar captura**.
2. En **Publicar para todos** presiona **Publicar ahora**. El archivo se cifra y se guarda directo en GitHub.
3. En uno o dos minutos el sitio se actualiza (recarga con Ctrl+F5).

Primera vez: en **Conexión con GitHub** captura usuario, repositorio, rama y un token fine-grained con permiso
*Contents: Read and write* solo sobre este repositorio. El token se guarda únicamente en ese navegador.

Sin token: **Descargar datos.js** y súbelo en *Add file → Upload files* (reemplaza al anterior).

## Cambiar la contraseña
Escribe la nueva (mínimo 10 caracteres) en el campo de contraseña antes de publicar y avisa a tu equipo.

## Importante
- Nunca subas un `datos.js` sin cifrar (el que empieza con `window.DATOS=`). El cifrado lo genera siempre el dashboard.
- Cada publicación queda en el historial del repositorio (pestaña *History* del archivo).
