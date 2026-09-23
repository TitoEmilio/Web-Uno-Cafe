# Uno Café · Sitio Web en Astro.js

Proyecto transformado de HTML estático a **Astro.js** preservando el 100% de la estética, arquitectura visual, tipografía (*Newsreader* y *Manrope*), tokens de color (*Kissa Sanctuary*) y componentes interactivos.

---

## 📁 Estructura del Proyecto

```text
uno-cafe-astro/
├── public/
│   └── favicon.svg               # Favicon con silueta artesanal de café
├── src/
│   ├── components/
│   │   ├── Header.astro          # Barra superior fija con logotipo y botón de menú
│   │   ├── Drawer.astro          # Menú lateral deslizante con enlaces y contacto
│   │   ├── BottomNav.astro       # Barra de navegación inferior fija con pestaña activa
│   │   ├── WhatsAppButton.astro  # Botón flotante directo a WhatsApp
│   │   └── Footer.astro          # Pie de página compartido con horarios y redes
│   ├── layouts/
│   │   └── Layout.astro          # Layout maestro con meta, fuentes y Tailwind
│   ├── pages/
│   │   ├── index.astro           # Inicio: Hero con parallax, filosofía, experiencia y luz
│   │   ├── carta.astro           # Carta: Menú completo con filtro dinámico por categoría
│   │   ├── nuestra-historia.astro# Historia: Métricas, fachada nocturna, manifiesto y oficio
│   │   ├── espacio.astro         # Espacio: Terraza, acústica, 4 pilares y reserva para grupos
│   │   └── ubicacion.astro       # Ubicación: Estado en vivo, accesos Maps/Waze y FAQ táctil
│   └── styles/
│       └── global.css            # Reglas base de Tailwind y scroll personalizado
├── astro.config.mjs              # Configuración de Astro con integración Tailwind
├── tailwind.config.mjs           # Tokens exactos de color, fuentes y espaciados
├── package.json                  # Dependencias y scripts
└── tsconfig.json                 # Configuración de TypeScript
```

---

## 🚀 Comandos Rápidos

En una terminal PowerShell o CMD dentro de la carpeta `uno-cafe-astro`:

```powershell
# 1. Iniciar servidor de desarrollo en http://localhost:4321
npm run dev

# 2. Compilar el proyecto para producción
npm run build

# 3. Previsualizar la versión de producción
npm run preview
```

---

## 🎨 Características Implementadas

1. **Fidelidad Visual Total**:
   - Paleta de diseño cálido *Japandi* (`surface`, `warm-ecru`, `soft-linen`, `espresso-deep`, `terracotta`, `secondary`).
   - Jerarquía tipográfica con serif editorial (*Newsreader*) y sans-serif humanista (*Manrope*).
   - Iconografía completa de Google Material Symbols Outlined.

2. **Interactividad**:
   - **Drawer Lateral Móvil**: Transiciones suaves al abrir/cerrar con fondo desenfocado (*backdrop-blur*).
   - **Filtro de Carta**: Botones sticky para alternar instantáneamente entre *Todas*, *Caliente*, *Frías*, *Dulce* y *Salado*.
   - **Acordeón FAQ**: Desplegable táctil en la sección de Ubicación con iconos animados.
   - **Efecto Parallax**: Desplazamiento suave en la imagen principal de la página de inicio.
   - **Navegación Inferior Activa**: Detecta automáticamente la página en la que se encuentra el usuario y resalta la pestaña correspondiente.
