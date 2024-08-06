## Como configurar la herramienta
### Instalación con curl (recomendado)
1. Ejecuta el siguiente comando en la terminal:
```bash
curl https://raw.githubusercontent.com/eliteasadev/astro-commit/main/index.js >> astro-commit.js 
```
2. Agrega el siguiente código al archivo package.json:
```json
"scripts": {
    "commit": "node astro-commit.js"
}
```
3. Ejecuta el comando `npm run commit` para iniciar la herramienta.


### Instalación manual
1. Crea un archivo llamado astro-commit.js en la raíz del proyecto.
2. Copia y pega el código del archivo [astro-commit.js](https://github.com/eliteasadev/astro-commit/blob/main/index.js) en el archivo que acabas de crear.
3. Agrega el siguiente código al archivo package.json:
```json
"scripts": {
    "commit": "node astro-commit.js"
}
```
4. Ejecuta el comando `npm run commit` para iniciar la herramienta.
