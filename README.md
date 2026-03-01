# Informacio-Turistica-Zaragoza
Zaragoza es historia romana, arte mudéjar, barroquismo impresionante y una de las mejores rutas de tapas de España.
Web informativa estática y responsive creada con Bootstrap 5 para promocionar Zaragoza como destino turístico en 2026.  
El sitio destaca el lema oficial de turismo de la ciudad: **"Zaragoza, la ciudad donde todo sucede"**, enfatizando su rico patrimonio (Basílica del Pilar, Palacio de la Aljafería), gastronomía (Ciudad Creativa UNESCO), el río Ebro y una agenda cultural vibrante todo el año.  
Incluye secciones sobre atractivos imprescindibles, eventos destacados (como las Fiestas del Pilar del 10 al 18 de octubre de 2026, Zaragoza Luce, eclipse solar parcial, etc.) y un diseño atractivo con hero icónico centrado en la Basílica del Pilar.   

**Sección “¿Por qué visitar Zaragoza?”** (id="que-ver"): grid con **2 columnas** en pantallas medianas y grandes (`row` + `col-md-6` para texto e imagen alineados).
- **Sección “Imprescindibles 2026”** (id="imprescindibles"): grid con **3 columnas** en pantallas medianas y grandes (`row` + `col-md-4` para las tres cards de atractivos principales).

**Commit 1: "Estructura base + Navbar + Hero con foto del Pilar"**  
  Creación del esqueleto HTML, inclusión de Bootstrap 5 vía CDN, navbar fixed-top responsive y hero con fondo panorámico real de la Basílica del Pilar (de Wikimedia Commons). Añadido overlay oscuro para legibilidad y texto centrado. Mejora: primera versión visual atractiva y responsive.

- **Commit 2: "Sección Qué ver (grid 2 columnas) + CSS propio inicial"**  
  Implementada la primera sección con grid de 2 columnas (texto + imagen lateral). Añadidos estilos personalizados para botones (rojo aragonés), hover en cards y sombras. Mejora: estructura principal del contenido, mejor legibilidad y coherencia visual.

- **Commit 3: "Sección Imprescindibles con cards + Footer"**  
  Añadida la segunda sección con grid de 3 cards (Pilar con foto real, Aljafería y El Tubo). Incluido footer con enlaces rápidos y copyright. Mejora: uso de componente card para presentar atractivos de forma atractiva y profesional, hover effect para interactividad.

- **Commit 4: "Sección Eventos 2026 + ajustes finales responsive y accesibilidad"**  
  Sección extra de eventos con list-group (incluyendo Fiestas del Pilar 10-18 octubre 2026 y otros hitos). Pequeños ajustes: text-shadow en hero para mejor contraste en móvil, transiciones suaves y comprobación responsive en distintos dispositivos. Mejora: contenido actualizado y completado, web lista para producción.

**Dificultad principal**: Lograr que el texto del hero (blanco sobre imagen panorámica del Pilar) fuera legible en todos los dispositivos, especialmente en móviles con pantallas pequeñas y brillo variable.  
**Solución**: Aumenté la opacidad del overlay oscuro (`linear-gradient rgba(0,0,0,0.65)`), añadí `text-shadow` fuerte (2px) y usé clases de Bootstrap para espaciado (`display-3`, `lead`, `fs-4`). Probado en DevTools responsive → resultado legible y atractivo en cualquier tamaño.
