# 🦄 Labubu World - Página Web

Una página web moderna y interactiva dedicada al adorable personaje Labubu de L.O.L Surprise!

## 📁 Estructura del Proyecto

```
LiamJAVA/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── images/             # Carpeta para imágenes locales
└── README.md           # Este archivo
```

## 🖼️ Cómo Agregar Imágenes Locales de Labubu

### Opción 1: Usar imágenes locales (Recomendado)

1. **Descarga imágenes de Labubu** de internet o usa tus propias fotos
2. **Colócalas en la carpeta `images/`** con nombres descriptivos:
   ```
   images/
   ├── labubu-classic.jpg
   ├── labubu-glitter.jpg
   ├── labubu-rainbow.jpg
   └── labubu-special.jpg
   ```

3. **Actualiza el CSS** en `styles.css`:
   ```css
   .card-image.labubu-1::before {
       background-image: url('images/labubu-classic.jpg');
   }
   
   .card-image.labubu-2::before {
       background-image: url('images/labubu-glitter.jpg');
   }
   
   .card-image.labubu-3::before {
       background-image: url('images/labubu-rainbow.jpg');
   }
   
   .card-image.labubu-4::before {
       background-image: url('images/labubu-special.jpg');
   }
   ```

4. **Actualiza el preloader** en `script.js`:
   ```javascript
   <img src="images/labubu-classic.jpg" alt="Labubu" style="width: 80px; height: 80px; border-radius: 50%; object-fit: cover;">
   ```

### Opción 2: Usar URLs de imágenes online

Actualmente la página usa imágenes de Unsplash como placeholder. Puedes reemplazarlas con URLs de imágenes reales de Labubu.

## 🎨 Personalización

### Colores
Los colores principales están definidos en variables CSS:
```css
:root {
    --primary-color: #ff6b9d;      /* Rosa principal */
    --secondary-color: #ffd1dc;    /* Rosa claro */
    --accent-color: #ff1493;       /* Magenta */
}
```

### Tipografía
La página usa la fuente Poppins de Google Fonts.

## 🚀 Funcionalidades

- ✅ Navegación responsive
- ✅ Animaciones suaves
- ✅ Formulario de contacto funcional
- ✅ Galería interactiva
- ✅ Efectos hover
- ✅ Contadores animados
- ✅ Sistema de notificaciones
- ✅ Preloader animado
- ✅ Cambio de tema

## 📱 Responsive Design

La página se adapta automáticamente a:
- 📱 Móviles (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1200px+)

## 🔧 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Grid y Flexbox
- **JavaScript ES6+** - Interactividad y animaciones
- **Font Awesome** - Iconos
- **Google Fonts** - Tipografía

## 🌟 Características Especiales

- **Animación de Labubu** - Personaje animado en el hero
- **Partículas flotantes** - Efecto visual en el fondo
- **Scroll suave** - Navegación fluida entre secciones
- **Validación de formularios** - Verificación de datos
- **Efectos de sonido** - Feedback auditivo (opcional)

## 📝 Notas

- Las imágenes actuales son placeholders de Unsplash
- Para mejor rendimiento, usa imágenes optimizadas (máximo 500KB cada una)
- Formatos recomendados: JPG, PNG, WebP
- Tamaño recomendado: 400x300px para las tarjetas

## 🎯 Próximas Mejoras

- [ ] Galería de imágenes con lightbox
- [ ] Modo oscuro completo
- [ ] Más animaciones de Labubu
- [ ] Integración con redes sociales
- [ ] Blog de noticias de Labubu

---

¡Disfruta explorando el mundo de Labubu! 🦄✨ 