# TechBlog Editor - Editor Avanzado para Blog de Tecnología

![TechBlog Editor](https://img.shields.io/badge/TechBlog-Editor-blue)
![Version](https://img.shields.io/badge/Version-2.0-green)
![License](https://img.shields.io/badge/Licencia-MIT-yellow)

Un editor de blog moderno y completo diseñado específicamente para contenido técnico, con soporte para código, terminales, iconos y elementos avanzados de formato.

## 🚀 Características Principales

### ✨ Funcionalidades del Editor
- **Editor WYSIWYG** con barra de herramientas completa
- **Vista previa en tiempo real** de tu contenido
- **Sistema de cursor inteligente** para inserción precisa
- **Soporte para múltiples elementos**:
  - Iconos FontAwesome (6 categorías)
  - Bloques de código con resaltado de sintaxis
  - Terminales estilo macOS/Linux
  - Capturas de código (CodeSnap)
  - Imágenes con alineación
  - Tablas personalizables
  - Videos embebidos
  - Enlaces

### 🎨 Formato Avanzado
- **Texto enriquecido**: Negrita, cursiva, subrayado
- **Alineación**: Izquierda, centro, derecha, justificado
- **Listas**: Numeradas y con viñetas
- **Fuentes**: Múltiples familias y tamaños
- **Colores**: Texto y fondo personalizables
- **Sangrías**: Control completo de indentación

### 💻 Elementos Técnicos
- **Resaltado de sintaxis** para 10+ lenguajes de programación
- **Terminales interactivas** con comandos predefinidos
- **CodeSnap** con botones de acción (copiar, descargar)
- **Iconos técnicos** categorizados (tecnología, archivos, interfaz)

## 🛠️ Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome 80+, Firefox 75+, Safari 13+)
- Conexión a internet (para CDNs)

### Uso Básico
1. **Clona o descarga** el archivo HTML
2. **Abre el archivo** en tu navegador
3. **Comienza a escribir** en el editor
4. **Usa la barra de herramientas** para formatear
5. **Inserta elementos** usando los botones correspondientes
6. **Genera el HTML** final cuando termines

## 📖 Guía de Uso

### 🔧 Barra de Herramientas

#### Grupo de Formato de Texto
- **Negrita** (`Ctrl+B`) - Texto en negrita
- **Cursiva** (`Ctrl+I`) - Texto en cursiva
- **Subrayado** (`Ctrl+U`) - Texto subrayado

#### Grupo de Alineación
- **Alinear izquierda** - Texto alineado a la izquierda
- **Centrar** - Texto centrado
- **Alinear derecha** - Texto alineado a la derecha
- **Justificar** - Texto justificado

#### Grupo de Listas
- **Lista numerada** - Lista ordenada
- **Lista con viñetas** - Lista no ordenada
- **Sangría** - Aumentar sangría
- **Quitar sangría** - Disminuir sangría

#### Grupo de Elementos
- **Enlace** - Insertar hipervínculo
- **Imagen** - Insertar imagen con alineación
- **Tabla** - Insertar tabla personalizable
- **Icono** - Insertar iconos FontAwesome

#### Grupo de Fuentes
- **Familia de fuente** - Cambiar tipo de letra
- **Tamaño de fuente** - Cambiar tamaño del texto

#### Grupo de Colores
- **Color de texto** - Cambiar color del texto
- **Color de fondo** - Cambiar color de fondo

#### Grupo de Elementos Técnicos
- **Terminal** - Insertar bloque de terminal
- **Código** - Insertar bloque de código
- **CodeSnap** - Insertar captura de código
- **Video** - Insertar video embebido

### 🖼️ Insertar Elementos

#### Iconos
1. Haz clic en **"Insertar icono"**
2. Selecciona una categoría (Tecnología, Social, Archivos, etc.)
3. Elige el icono deseado
4. Ajusta tamaño y color
5. Haz clic en **"Insertar icono"**

#### Imágenes
1. Haz clic en **"Insertar imagen"**
2. Ingresa la URL de la imagen
3. Agrega texto alternativo
4. Define el ancho (opcional)
5. Selecciona la alineación
6. Haz clic en **"Insertar"**

#### Terminales
1. Haz clic en **"Insertar terminal"**
2. Configura usuario y directorio
3. Escribe el comando o usa uno predefinido
4. Agrega la salida del comando
5. Haz clic en **"Insertar terminal"**

#### Bloques de Código
1. Haz clic en **"Insertar código"**
2. Selecciona el lenguaje
3. Escribe o pega tu código
4. Haz clic en **"Insertar código"**

### ⌨️ Comandos de Terminal Predefinidos

El editor incluye comandos comunes preconfigurados:

- `ls -la` - Listar archivos con detalles
- `git status` - Estado del repositorio Git
- `python --version` - Versión de Python
- `node -v` - Versión de Node.js
- `docker ps` - Contenedores Docker activos
- `npm install react` - Instalar paquete npm

## 🎯 Características Técnicas

### Tecnologías Utilizadas
- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript Vanilla** - Funcionalidad sin dependencias pesadas
- **FontAwesome 6** - Iconos vectoriales
- **Highlight.js** - Resaltado de sintaxis
- **Bootstrap 5** - Componentes de interfaz

### Estructura de Archivos
```
techblog-editor/
│
├── index.html          # Archivo principal
├── README.md          # Documentación
└── assets/            # Recursos (opcional)
    ├── images/
    └── styles/
```

### Personalización

#### Colores y Temas
El editor usa variables CSS para una fácil personalización:

```css
:root {
    --primary: #2563eb;
    --secondary: #64748b;
    --terminal: #0f172a;
    --success: #10b981;
    /* ... más variables */
}
```

#### Agregar Nuevos Iconos
Edita el objeto `iconCategories` en el JavaScript:

```javascript
const iconCategories = {
    nueva_categoria: [
        'fa-nuevo-icono',
        'fa-otro-icono'
    ]
};
```

## 📋 Atajos de Teclado

| Función | Atajo | Descripción |
|---------|-------|-------------|
| Negrita | `Ctrl+B` | Texto en negrita |
| Cursiva | `Ctrl+I` | Texto en cursiva |
| Subrayado | `Ctrl+U` | Texto subrayado |
| Guardar | `Ctrl+S` | Generar HTML |
| Limpiar | `Ctrl+Shift+L` | Limpiar editor |
| Cerrar modal | `Esc` | Cerrar ventana modal |

## 🚨 Solución de Problemas

### Problemas Comunes

#### Los iconos no se muestran
- Verifica la conexión a internet
- Comprueba que FontAwesome esté cargado

#### El resaltado de código no funciona
- Asegúrate de que Highlight.js esté cargado
- Verifica la consola del navegador para errores

#### Los elementos no se insertan en la posición correcta
- Haz clic en el editor antes de insertar
- Verifica que el cursor esté visible

#### Los modales no se cierran
- Haz clic fuera del modal o presiona `Esc`
- Verifica que no haya errores en la consola

### Compatibilidad
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ⚠️ Internet Explorer - No compatible

## 🔧 Desarrollo

### Estructura del Código

#### Componentes Principales
- **Sistema de Cursor**: Maneja posiciones y inserciones
- **Gestor de Modales**: Controla ventanas emergentes
- **Sistema de Iconos**: Categoriza y muestra iconos
- **Generador de HTML**: Produce código final

#### Funciones Clave
```javascript
// Sistema de cursor
saveCursorPosition()
restoreCursorPosition()
insertHTMLAtCursor()

// Gestión de elementos
insertElementAtCursor(type)
updatePreview()
generateHTML()
```

### Extensibilidad
Para agregar nuevos tipos de elementos:

1. Agrega el botón en la barra de herramientas
2. Crea el modal correspondiente
3. Implementa la función en `insertElementAtCursor()`
4. Actualiza la vista previa si es necesario

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Soporte

Si encuentras problemas o tienes preguntas:

1. Revisa la sección de solución de problemas
2. Verifica la consola del navegador para errores
3. Crea un issue en el repositorio

## 🔄 Historial de Versiones

### v2.0 (Actual)
- ✅ Sistema de cursor mejorado
- ✅ Iconos funcionando correctamente
- ✅ Terminales sin interferencias de teclado
- ✅ Vista previa en tiempo real
- ✅ Comandos predefinidos

### v1.0
- Versión inicial con funcionalidades básicas

---

**Desarrollado con ❤️ para la comunidad técnica**

¿Encontraste útil este editor? ¡Considera darle una estrella ⭐ en el repositorio!
