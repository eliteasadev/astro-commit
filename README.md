<h1 align="center">🚀 Astro Commit</h1>

## Configuración de la herramienta
### Instalación con curl (recomendado)
1. Ejecuta el siguiente comando en la terminal estando en la raíz del proyecto:
```bash
curl https://raw.githubusercontent.com/eliteasadev/astro-commit/main/index.js >> astro-commit.js 
```
2. Agrega el siguiente código al archivo package.json:
```json
"scripts": {
    "commit": "node astro-commit.js"
}
```
3. Agrega inquirer a las dependencias de desarrollo del proyecto:
```bash
npm install @inquirer/prompts --save-dev
```

4. Ejecuta el comando `npm run commit` para iniciar la herramienta.

<span style="color:red; font-weight:bold;">NOTA IMPORTANTE</span>: Antes de ejecutar el comando `npm run commit`, asegúrate de agregaste los cambios realizados al stage de git. Puedes usar el comando `git add .` para agregarlos.

### Instalación manual
1. Crea un archivo llamado astro-commit.js en la raíz del proyecto.
2. Copia y pega el código del archivo [astro-commit.js](https://github.com/eliteasadev/astro-commit/blob/main/index.js) en el archivo que acabas de crear.
3. Agrega el siguiente código al archivo package.json:
```json
"scripts": {
    "commit": "node astro-commit.js"
}
```
3. Agrega inquirer a las dependencias de desarrollo del proyecto:
```bash
npm install @inquirer/prompts --save-dev
```
4. Ejecuta el comando `npm run commit` para iniciar la herramienta.
