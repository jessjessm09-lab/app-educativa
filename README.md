# 🎓 App Educativa - Lengua y Literatura

Una aplicación web interactiva para docentes de lengua y literatura que permite crear juegos educativos personalizados para estudiantes de secundaria.

![App Educativa](https://img.shields.io/badge/Versión-1.0-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

## ✨ Características

### 📚 Gestión de Contenidos
- **Múltiples Cursos**: Organiza tus contenidos por año (2do, 3ro, etc.)
- **Temas Personalizables**: Crea temas específicos para cada curso
- **Almacenamiento Local**: Todos los datos se guardan automáticamente en el navegador

### 🎮 Juegos Interactivos
1. **🧠 Memoria**: Encuentra las parejas de conceptos y categorías
2. **📋 Clasificación**: Arrastra palabras a sus categorías correctas
3. **❓ Quiz**: Responde preguntas de opción múltiple
4. **✓✗ Verdadero/Falso**: Valida afirmaciones sobre los conceptos

### 🎡 Rueda de Nombres
- Sortea turnos en clase de forma visual y divertida
- Ingresa los nombres de tus estudiantes
- Animación de ruleta interactiva

## 🚀 Instalación y Uso

### Opción 1: Usar Directamente (Recomendado)
1. Visita la versión en línea: [App Educativa](https://tu-usuario.github.io/app-educativa)
2. ¡Comienza a usar la app inmediatamente!

### Opción 2: Descargar Localmente
1. Descarga el archivo `index.html`
2. Abre el archivo en tu navegador (Chrome, Firefox, Edge, Safari)
3. ¡Listo para usar!

### Opción 3: Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/app-educativa.git
cd app-educativa
```
Luego abre `index.html` en tu navegador.

## 📖 Guía de Uso

### 1. Configuración Inicial

#### Agregar un Curso
1. Ve a la pestaña **"Administrar"**
2. En "Agregar Nuevo Curso", ingresa el nombre (ej: "2do Año")
3. Haz clic en **"Agregar Curso"**

#### Agregar un Tema
1. Selecciona el curso en el menú desplegable
2. Ingresa el nombre del tema (ej: "Clases de Palabras")
3. Agrega el contenido en formato: `concepto|categoría`
   - Ejemplo:
   ```
   sustantivo|Clase de palabra
   adjetivo|Clase de palabra
   verbo|Clase de palabra
   mesa|Sustantivo
   correr|Verbo
   azul|Adjetivo
   ```
4. Haz clic en **"Agregar Tema"**

### 2. Usar los Juegos

1. Ve a la pestaña **"Juegos"**
2. Selecciona un **Curso**
3. Selecciona un **Tema**
4. Elige el **Juego** que quieras usar
5. ¡Los estudiantes aprenden jugando!

### 3. Rueda de Nombres

1. Ve a la pestaña **"Rueda de Nombres"**
2. Ingresa los nombres de tus estudiantes (uno por línea)
3. Haz clic en **"Configurar Rueda"**
4. Presiona **"Girar Rueda"** para sortear

## 📱 Compatibilidad

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari
- ✅ Dispositivos móviles (tablets y smartphones)
- ✅ Funciona sin conexión a Internet

## 💾 Almacenamiento de Datos

Todos los datos (cursos, temas, contenidos) se guardan automáticamente en el **LocalStorage** del navegador. Esto significa:

- ✅ No necesitas cuenta ni registro
- ✅ Tus datos persisten entre sesiones
- ✅ Funciona completamente offline
- ⚠️ Si limpias los datos del navegador, se perderán los contenidos guardados

### Exportar/Respaldar Datos
Para hacer una copia de seguridad de tus datos:
1. Abre la consola del navegador (F12)
2. Escribe: `localStorage.getItem('appEducativaData')`
3. Copia el resultado y guárdalo en un archivo de texto

Para restaurar:
1. Abre la consola del navegador (F12)
2. Escribe: `localStorage.setItem('appEducativaData', 'TU_DATOS_AQUI')`

## 🎨 Personalización

El proyecto está construido con HTML, CSS y JavaScript puro, sin dependencias externas. Puedes personalizar:

- **Colores**: Modifica los gradientes en el `<style>` de `index.html`
- **Juegos**: Agrega nuevos tipos de juegos en el archivo JavaScript
- **Contenido de Ejemplo**: Cambia los datos predeterminados en la función `loadData()`

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar la app:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📝 Ideas para Futuras Mejoras

- [ ] Exportar/importar temas en formato JSON
- [ ] Estadísticas de progreso de estudiantes
- [ ] Más tipos de juegos (sopa de letras, crucigramas)
- [ ] Modo multijugador
- [ ] Generación automática de contenido con IA
- [ ] Impresión de fichas de trabajo

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍🏫 Para Docentes

Esta aplicación fue creada pensando en facilitar la enseñanza de Lengua y Literatura, pero puede adaptarse fácilmente para otras materias:

- **Matemáticas**: Fórmulas, conceptos geométricos
- **Ciencias**: Elementos químicos, partes del cuerpo
- **Historia**: Fechas, personajes, eventos
- **Idiomas**: Vocabulario, gramática

## 📧 Contacto

Si tienes preguntas, sugerencias o necesitas ayuda, no dudes en:
- Abrir un [Issue](https://github.com/tu-usuario/app-educativa/issues)
- Contactarme por email: tu-email@ejemplo.com

---

Hecho con ❤️ para educadores que quieren innovar en el aula.

**¡Que tus estudiantes aprendan divirtiéndose!** 🎉
