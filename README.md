# 🏆 Tier Maker

Una aplicación web interactiva para crear listas de clasificación (tier lists) personalizables con una interfaz moderna y funcional.

![Tier Maker Demo](https://via.placeholder.com/800x400/111111/ffffff?text=Tier+Maker+Demo)

## ✨ Características

### 🎨 Interfaz Personalizable
- **Colores personalizables**: Cada tier tiene un selector de color integrado para personalizar la apariencia
- **Etiquetas editables**: Haz clic en cualquier etiqueta (S, A, B, C, D, E) para cambiar el texto
- **Diseño responsive**: Optimizado para dispositivos móviles y desktop

### 🖼️ Gestión de Imágenes
- **Carga múltiple**: Sube varias imágenes a la vez desde tu dispositivo
- **Drag & Drop**: Arrastra archivos directamente desde tu explorador de archivos
- **Zoom de imágenes**: Doble clic en cualquier imagen para verla en tamaño completo
- **Vista previa durante arrastre**: Visualiza dónde se colocará la imagen mientras la arrastras

### 🎯 Funcionalidades Avanzadas
- **Arrastrar y soltar**: Mueve imágenes entre diferentes tiers de forma intuitiva
- **Reset rápido**: Botón para devolver todas las imágenes al área de selección
- **Exportar tier list**: Guarda tu tier list como imagen PNG
- **Animaciones suaves**: Transiciones fluidas para una mejor experiencia de usuario

## 🚀 Demo en Vivo

[Ver Demo]([https://tu-tiermaker.vercel.app]) 

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Diseño moderno con variables CSS y flexbox
- **JavaScript (ES6+)**: Lógica interactiva con módulos nativos
- **html2canvas**: Para la exportación de imágenes
- **Rspack**: Bundler rápido para desarrollo y build
- **Vercel**: Deployment y hosting

## 📦 Instalación y Uso

### Prerrequisitos
- Node.js (versión 16 o superior)
- npm o yarn

### Instalación Local

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/tier-maker.git
   cd tier-maker
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**
   ```bash
   npm run dev
   ```

4. **Abre tu navegador**
   ```
   http://localhost:3000
   ```

### Build para Producción

```bash
npm run build
```

## 🎮 Cómo Usar

1. **Cargar Imágenes**
   - Haz clic en el botón ➕ para seleccionar archivos
   - O arrastra imágenes directamente al área de selección

2. **Organizar en Tiers**
   - Arrastra las imágenes desde el área de selección a cualquier tier
   - Mueve imágenes entre diferentes tiers según prefieras

3. **Personalizar**
   - Haz clic en las etiquetas (S, A, B, etc.) para editarlas
   - Usa los selectores de color para cambiar los colores de cada tier

4. **Ver en Detalle**
   - Doble clic en cualquier imagen para verla ampliada

5. **Resetear**
   - Usa el botón 🔄 para devolver todas las imágenes al área de selección

6. **Guardar**
   - Haz clic en el botón 💾 para descargar tu tier list como imagen PNG

## 🎯 Casos de Uso

- **Gaming**: Clasificar personajes, armas, o niveles de videojuegos
- **Entretenimiento**: Rankear películas, series, canciones o artistas
- **Educación**: Organizar conceptos por importancia o dificultad
- **Trabajo**: Priorizar tareas o evaluar opciones
- **Personal**: Cualquier clasificación que necesites hacer

## 🔧 Estructura del Proyecto

```
tier-maker/
├── index.html          # Página principal con toda la funcionalidad
├── package.json         # Dependencias y scripts
├── rspack.config.mjs    # Configuración de Rspack
├── vercel.json         # Configuración de deployment
└── src/
    ├── index.js        # Punto de entrada alternativo
    └── index.css       # Estilos alternativos
```

## 🌐 Deployment

Este proyecto está configurado para desplegarse automáticamente en Vercel:

1. **Conecta tu repositorio** a Vercel
2. **Deploy automático** en cada push a main
3. **Preview deploys** para pull requests

### Variables CSS Personalizables

```css
:root {
  --color-s: #ff7f80;  /* Tier S - Rojo claro */
  --color-a: #ffc07f;  /* Tier A - Naranja */
  --color-b: #ffdf80;  /* Tier B - Amarillo */
  --color-c: #fdff7f;  /* Tier C - Amarillo verdoso */
  --color-d: #bfff7f;  /* Tier D - Verde claro */
  --color-e: #7fff7f;  /* Tier E - Verde */
}
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📋 Roadmap

- [ ] Guardar tier lists en localStorage
- [ ] Compartir tier lists por URL
- [ ] Más opciones de personalización visual
- [ ] Soporte para categorías personalizadas
- [ ] Modo oscuro/claro
- [ ] Plantillas predefinidas

## 🐛 Problemas Conocidos

- La exportación de imágenes puede tardar unos segundos en tier lists grandes
- El drag & drop desde URLs externas no está soportado (solo archivos locales)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👤 Autor

**Tu Nombre**
- GitHub: [@tu-usuario]([https://github.com/tu-usuario](https://github.com/SaKio1985))
- LinkedIn: [Tu Perfil]((https://www.linkedin.com/in/iban-dorado-171a4a24b/))

---

⭐ ¡Dale una estrella si te gustó este proyecto!

## 📸 Screenshots

### Vista Principal
![Vista Principal](https://res.cloudinary.com/dko8avpyk/image/upload/v1749729804/Tier_Maker_mthasj.png)

### Personalizando Colores
![Personalizando Colores](https://res.cloudinary.com/dko8avpyk/image/upload/v1749729804/Tier-cambio_color_untjui.png)

### Tier List Completada
![Tier List Completada](https://res.cloudinary.com/dko8avpyk/image/upload/v1749729804/tier_final_ogxtjb.png)
