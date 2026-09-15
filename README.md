# Portal Cumulus Finance

Página web estática en español preparada para publicarse gratuitamente con GitHub Pages.

## Contenido del proyecto

```text
cumulus-finance-portal/
├── index.html
├── styles.css
├── app.js
├── README.md
└── assets/
    ├── cisco-connect-latam.png
    ├── cumulus-logo.svg
    └── cisco-connect-latam.svg
```

La página no requiere servidor, base de datos, Node.js ni instalación de paquetes. GitHub Pages puede publicarla directamente.

## Publicación paso a paso usando el navegador

### Paso 1: descargar y descomprimir

1. Descarga `cumulus-finance-portal.zip`.
2. En tu Mac, abre **Downloads**.
3. Haz doble clic sobre el ZIP.
4. Se creará una carpeta llamada `cumulus-finance-portal`.

### Paso 2: crear el repositorio

1. Abre [github.com](https://github.com/) e inicia sesión.
2. En la esquina superior derecha, selecciona el símbolo **+**.
3. Selecciona **New repository**.
4. En **Repository name**, escribe `cumulus-finance-portal`.
5. En **Description**, escribe `Portal web de Cumulus Finance para Cisco Connect LatAm 2026`.
6. Selecciona **Public**.
7. No selecciones **Add a README file**, porque el paquete ya incluye uno.
8. No agregues `.gitignore` ni licencia.
9. Selecciona **Create repository**.

### Paso 3: subir los archivos

1. Dentro del repositorio nuevo, selecciona **uploading an existing file**. Si no aparece, usa **Add file > Upload files**.
2. Abre en Finder la carpeta `cumulus-finance-portal` que descomprimiste.
3. Selecciona `index.html`, `styles.css`, `app.js`, `README.md` y la carpeta `assets`.
4. Arrástralos al área de carga de GitHub.
5. Confirma que `index.html` quede en la raíz del repositorio, no dentro de otra carpeta adicional.
6. En **Commit message**, escribe `Publicar portal inicial de Cumulus Finance`.
7. Selecciona **Commit changes**.

Importante: no subas solamente el archivo ZIP. GitHub Pages necesita ver `index.html` directamente dentro del repositorio.

### Paso 4: activar GitHub Pages

1. En el repositorio, abre **Settings**.
2. En la columna izquierda, abre **Pages**.
3. En **Build and deployment**, busca **Source**.
4. Selecciona **Deploy from a branch**.
5. En **Branch**, selecciona `main`.
6. En la carpeta, selecciona `/(root)`.
7. Selecciona **Save**.

### Paso 5: abrir la página pública

1. Espera entre uno y cinco minutos.
2. Actualiza la sección **Settings > Pages**.
3. GitHub mostrará el mensaje **Your site is live at** seguido de la dirección.
4. Si el usuario de GitHub es `carolmorcisco`, la dirección esperada será:

```text
https://carolmorcisco.github.io/cumulus-finance-portal/
```

### Paso 6: verificar

1. Abre la dirección pública.
2. Confirma que aparece el logo de Cumulus Finance.
3. Confirma que se ve la referencia de Cisco Connect LatAm.
4. Confirma que las cinco tarjetas financieras aparecen en la pantalla principal.
5. Prueba la página desde una ventana privada para confirmar que es pública.

## Actualizar la página después

1. En GitHub, abre el repositorio.
2. Selecciona el archivo que deseas cambiar.
3. Selecciona el ícono de lápiz **Edit this file**.
4. Realiza el cambio.
5. Selecciona **Commit changes**.
6. GitHub Pages publicará la nueva versión automáticamente.

## Logos

El HTML intenta usar primero el PNG de Cumulus Finance proporcionado para la demostración. Si ese servidor bloquea la imagen, la página cambia automáticamente al archivo local `assets/cumulus-logo.svg`.

El encabezado utiliza el archivo local `assets/cisco-connect-latam.png` con el logotipo y las fechas oficiales del evento. También enlaza al sitio oficial de Cisco Connect LatAm.
