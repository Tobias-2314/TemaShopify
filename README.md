# 🛍️ Tema Shopify - Landing Page Estilo Dropverse

Tema Dawn transformado en una landing page de producto único de alta conversión, inspirado en **dropverse.es**.

## ✨ Características Principales

### 🎨 100% Personalizable Sin Código
- Todas las secciones configurables desde el Theme Customizer de Shopify
- Sin necesidad de conocimientos de programación
- Cambios en tiempo real

### 🚀 7 Secciones CRO Optimizadas

1. **Hero con Urgencia** - Badge de urgencia, rating, selector de variantes visual
2. **Bundle Selector** - Sistema de descuentos automáticos por cantidad
3. **Timeline de Entrega** - Proceso visual con fechas calculadas
4. **Instagram Stories** - Prueba social en formato familiar
5. **Testimonios con Fotos** - Reseñas verificadas con imágenes
6. **Tabla Comparativa** - "Nosotros vs Otros" con checkmarks
7. **Sticky Add to Cart** - Botón persistente siempre visible

### 🎯 Optimizaciones de Conversión

- ✅ Urgencia y escasez
- ✅ Prueba social múltiple
- ✅ Bundles para aumentar AOV (+25-40%)
- ✅ CTA de alto contraste (#0059B2)
- ✅ Mobile-first responsive
- ✅ Performance optimizado

## 📦 Archivos Incluidos

### Secciones Liquid
```
sections/
├── urgency-hero.liquid
├── bundle-selector.liquid
├── delivery-timeline.liquid
├── comparison-table.liquid
├── instagram-stories.liquid
├── photo-testimonials.liquid
└── sticky-atc.liquid
```

### Assets CSS
```
assets/
└── cro-optimizations.css
```

### Configuración
```
layout/
└── theme.liquid (modificado)

templates/
└── product.json (configurado)
```

## 🚀 Instalación

### 1. Descargar el Tema
```bash
git clone https://github.com/Tobias-2314/TemaShopify.git
cd TemaShopify
```

### 2. Comprimir para Shopify
```bash
# Comprimir todo el contenido en un archivo ZIP
zip -r tema-dropverse.zip *
```

### 3. Subir a Shopify
1. Ve a **Tienda Online** → **Temas**
2. Haz clic en **Añadir tema** → **Subir archivo ZIP**
3. Selecciona el archivo `tema-dropverse.zip`
4. Espera a que se suba y procese

### 4. Personalizar
1. Haz clic en **Personalizar** en el tema
2. Selecciona una página de producto
3. Todas las secciones estarán disponibles en el panel izquierdo
4. Modifica textos, colores, imágenes según tu marca

## 🎨 Personalización

### Cambiar Colores Principales

Edita `assets/cro-optimizations.css`:

```css
:root {
  --cro-primary-blue: #0059B2;      /* Color principal */
  --cro-urgent-red: #FF5252;        /* Color de urgencia */
  --cro-success-green: #4CAF50;     /* Color de éxito */
  --cro-star-yellow: #FFB800;       /* Color de estrellas */
}
```

### Configurar Bundles

1. Ve a **Personalizar** → Página de producto
2. Selecciona **Bundle Selector**
3. Añade bundles con **"Añadir bundle"**
4. Configura:
   - Cantidad de productos
   - Porcentaje de descuento
   - Marcar como "Más Popular"

**Ejemplo:**
```
Bundle 1: 1 unidad, 0% descuento
Bundle 2: 2 unidades, 15% descuento ⭐ MÁS POPULAR
Bundle 3: 4 unidades, 30% descuento
```

### Añadir Testimonios

1. Selecciona **Testimonios con Fotos**
2. Añade testimonio con **"Añadir testimonio"**
3. Sube foto del cliente
4. Configura:
   - Nombre
   - Rating (1-5 estrellas)
   - Texto del testimonio
   - Mostrar badge "Compra Verificada"

## 📱 Responsive Design

Todas las secciones son completamente responsive:

- **Mobile** (< 750px): Layout de 1 columna, sticky ATC optimizado
- **Tablet** (750px - 989px): Layout de 2 columnas
- **Desktop** (> 990px): Layout completo de 3-4 columnas

## ⚡ Performance

### Optimizaciones Implementadas

- ✅ Lazy loading de imágenes
- ✅ CSS minificado
- ✅ Animaciones eliminadas/reducidas
- ✅ Variables CSS para rápida personalización
- ✅ Transiciones suaves (0.3s)

### Resultados Esperados

- **PageSpeed Mobile:** >85
- **PageSpeed Desktop:** >90
- **Tasa de Conversión:** +15-30%
- **AOV:** +25-40%

## 🎯 Orden Óptimo de Secciones

El template está configurado con el orden perfecto para conversión:

1. **Urgency Hero** - Captura atención
2. **Bundle Selector** - Incrementa AOV
3. **Delivery Timeline** - Reduce fricción
4. **Instagram Stories** - Prueba social visual
5. **Photo Testimonials** - Reseñas detalladas
6. **Comparison Table** - Ventajas competitivas
7. **Sticky ATC** - Siempre disponible

## 🛠️ Tecnologías

- **Shopify Liquid** - Template engine
- **CSS3** - Estilos con variables CSS
- **JavaScript Vanilla** - Sin dependencias
- **Mobile-First** - Diseño responsive

## 📊 Elementos de Dropverse Implementados

| Elemento | Estado |
|----------|--------|
| Badge de urgencia | ✅ |
| Rating prominente | ✅ |
| Selector de variantes visual | ✅ |
| Bundles con descuentos | ✅ |
| Badge "Más Popular" | ✅ |
| Timeline de entrega | ✅ |
| Tabla comparativa | ✅ |
| Instagram stories | ✅ |
| Testimonios con fotos | ✅ |
| Sticky ATC | ✅ |
| Iconos de pago | ✅ |

## 📝 Documentación

Para documentación detallada sobre cómo usar cada sección, consulta los archivos:

- `implementation_plan.md` - Plan técnico de implementación
- `walkthrough.md` - Guía paso a paso de uso

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está basado en el tema Dawn de Shopify.

## 👤 Autor

**Tobias**
- GitHub: [@Tobias-2314](https://github.com/Tobias-2314)

## 🙏 Agradecimientos

- Inspirado en [dropverse.es](https://dropverse.es)
- Basado en el tema Dawn de Shopify
- Optimizaciones CRO basadas en mejores prácticas de la industria

---

⭐ Si este tema te ayuda a aumentar tus ventas, considera darle una estrella al repositorio!
