# 📤 Guía para Subir a GitHub

Sigue estos pasos para publicar tu App Educativa en GitHub y hacerla accesible en línea.

## Paso 1: Crear Repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) e inicia sesión
2. Haz clic en el botón **"+"** en la esquina superior derecha
3. Selecciona **"New repository"**
4. Configura tu repositorio:
   - **Nombre**: `app-educativa` (o el nombre que prefieras)
   - **Descripción**: "Aplicación educativa interactiva para Lengua y Literatura"
   - **Visibilidad**: Público (para poder usar GitHub Pages)
   - **NO** marques "Add a README file" (ya lo tenemos)
5. Haz clic en **"Create repository"**

## Paso 2: Subir los Archivos

### Opción A: Usando GitHub Web (Más Fácil)

1. En tu nuevo repositorio, haz clic en **"uploading an existing file"**
2. Arrastra y suelta TODOS estos archivos:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Escribe un mensaje de commit: "Primera versión de la app educativa"
4. Haz clic en **"Commit changes"**

### Opción B: Usando Git desde la Terminal

Si tienes Git instalado, abre la terminal en la carpeta del proyecto y ejecuta:

```bash
# Inicializar repositorio
git init

# Agregar todos los archivos
git add .

# Hacer el primer commit
git commit -m "Primera versión de la app educativa"

# Conectar con GitHub (reemplaza TU-USUARIO y TU-REPO)
git remote add origin https://github.com/TU-USUARIO/app-educativa.git

# Subir los archivos
git branch -M main
git push -u origin main
```

## Paso 3: Activar GitHub Pages

1. En tu repositorio de GitHub, ve a **"Settings"** (Configuración)
2. En el menú lateral, haz clic en **"Pages"**
3. En **"Source"** (Fuente), selecciona:
   - Branch: `main`
   - Folder: `/ (root)`
4. Haz clic en **"Save"**
5. Espera 1-2 minutos y actualiza la página
6. Verás un mensaje: **"Your site is published at https://TU-USUARIO.github.io/app-educativa/"**

## Paso 4: ¡Compartir tu App!

Tu app ya está en línea en:
```
https://TU-USUARIO.github.io/app-educativa/
```

Comparte este link con:
- ✅ Tus estudiantes
- ✅ Otros docentes
- ✅ Redes sociales educativas
- ✅ Tu comunidad educativa

## 🔄 Actualizar la App

Cuando hagas cambios y quieras actualizar la versión en línea:

### Usando GitHub Web:
1. Ve al archivo que quieres modificar
2. Haz clic en el ícono del lápiz (editar)
3. Realiza tus cambios
4. Haz clic en **"Commit changes"**

### Usando Git:
```bash
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios se verán en línea en 1-2 minutos.

## 🎨 Personalizar el README

No olvides actualizar en el archivo `README.md`:
- Reemplaza `tu-usuario` con tu nombre de usuario de GitHub
- Actualiza la información de contacto
- Agrega capturas de pantalla si quieres

## 📸 Agregar Capturas de Pantalla (Opcional)

Para hacer el README más atractivo:

1. Toma capturas de pantalla de tu app
2. Crea una carpeta llamada `images/` en tu repositorio
3. Sube las imágenes ahí
4. En el README, agrega:
   ```markdown
   ![Pantalla Principal](images/screenshot1.png)
   ```

## ⚡ Consejos

- ✅ Usa nombres descriptivos en tus commits
- ✅ Actualiza el README con ejemplos de uso
- ✅ Agrega un archivo CHANGELOG.md para llevar control de versiones
- ✅ Comparte el repositorio en comunidades educativas

## 🆘 Problemas Comunes

### "Mi app no se ve en GitHub Pages"
- Verifica que el archivo se llame `index.html` (no `app-educativa.html`)
- Espera 5-10 minutos después de activar GitHub Pages
- Revisa que el repositorio sea público

### "Los estilos no cargan"
- Asegúrate de que todo el CSS esté dentro del archivo HTML
- Limpia el caché del navegador (Ctrl + Shift + R)

### "Perdí mis datos al actualizar"
- Los datos están en el navegador del usuario, no se pierden al actualizar la app
- Recuerda que cada navegador tiene su propio almacenamiento

---

¿Necesitas ayuda? Abre un Issue en GitHub o consulta la [documentación de GitHub Pages](https://docs.github.com/es/pages).

¡Buena suerte con tu proyecto! 🚀
