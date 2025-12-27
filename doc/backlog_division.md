# SOMOS IDENTIDAD - Product Backlog
## 🤖 Claude crea UI | 👨‍💻 Estudiante crea Funcionalidades

---

# 🎯 EPIC 1: Tienda Online SOMOS IDENTIDAD

**División de responsabilidades:**
- 🤖 **Claude:** Crea todos los componentes visuales (HTML + CSS/Bootstrap estático)
- 👨‍💻 **Estudiante:** Implementa todas las funcionalidades e interacciones (JavaScript)

---

## 📦 FEATURE 1.1: Landing Page / Home

### 📘 HU-1.1.1: Ver Hero Section
**Prioridad:** Alta | **Sprint:** 1 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Estructura HTML del hero (section, headings, botón CTA)
- [ ] **C2:** Estilos CSS (gradient, tipografía, centrado, hover effects, responsive)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** (Futuro) Animación de entrada fade-in

---

### 📘 HU-1.1.2: Ver Productos Destacados
**Prioridad:** Alta | **Sprint:** 1 | **Puntos:** 3

#### 🤖 Claude crea:
- [ ] **C1:** Sección con título y grid Bootstrap
- [ ] **C2:** Card de producto (imagen, título, precio, botón) con estilos y hover
- [ ] **C3:** Responsive (3-2-1 columnas)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Cargar productos desde array JS y renderizar dinámicamente
- [ ] **E2:** Botón "Ver más" con paginación

---

### 📘 HU-1.1.3: Ver Sección "Sobre Nosotros"
**Prioridad:** Media | **Sprint:** 1 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Layout 2 columnas (texto + imagen), estilos, responsive

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** (Futuro) Animación scroll con Intersection Observer

---

## 📦 FEATURE 1.2: Navegación Global

### 📘 HU-1.2.1: Navegar por el sitio
**Prioridad:** Alta | **Sprint:** 1 | **Puntos:** 3

#### 🤖 Claude crea:
- [ ] **C1:** Navbar Bootstrap (logo, links, estructura)
- [ ] **C2:** Estilos (background, hover cyan, position sticky)
- [ ] **C3:** Hamburger menu responsive con Bootstrap collapse

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Toggle menu móvil (usar data-bs-toggle de Bootstrap, sin JS propio)
- [ ] **E2:** (Futuro) Highlight de página activa
- [ ] **E3:** (Futuro) Scroll spy (cambiar opacidad navbar)

---

### 📘 HU-1.2.2: Ver Footer informativo
**Prioridad:** Media | **Sprint:** 1 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Footer 3 columnas (Info, Links, Redes), íconos
- [ ] **C2:** Estilos, separadores, responsive

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Actualizar año dinámicamente con `new Date().getFullYear()`

---

## 📦 FEATURE 1.3: Catálogo de Productos

### 📘 HU-1.3.1: Ver catálogo de productos
**Prioridad:** Alta | **Sprint:** 2 | **Puntos:** 3

#### 🤖 Claude crea:
- [ ] **C1:** Página `catalog.html` completa (navbar + footer)
- [ ] **C2:** Grid con 12 cards de productos mockup (badges variados)
- [ ] **C3:** Responsive (4-3-2-1 columnas)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Crear `products.js` y renderizar cards dinámicamente
- [ ] **E2:** Implementar paginación (8 productos por página)

---

### 📘 HU-1.3.2: Ver detalle de producto
**Prioridad:** Alta | **Sprint:** 2 | **Puntos:** 4

#### 🤖 Claude crea:
- [ ] **C1:** Página `product-detail.html` (layout 2 columnas)
- [ ] **C2:** Sección imagen grande (500x500px)
- [ ] **C3:** Sección info (título, precio, descripción, rating)
- [ ] **C4:** Selectores visuales (botones tallas, input cantidad)
- [ ] **C5:** Botón "Agregar al carrito" grande
- [ ] **C6:** Responsive (stack en móvil)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Leer ID de URL y cargar producto desde array
- [ ] **E2:** Lógica selector de tallas (solo una activa)
- [ ] **E3:** Lógica selector de cantidad (min 1, max 10)
- [ ] **E4:** Guardar en localStorage al "Agregar al carrito"

---

### 📘 HU-1.3.3: Filtrar productos por categoría
**Prioridad:** Media | **Sprint:** 3 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Barra de filtros (botones categorías, estados, badges de conteo)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Filtrar productos por categoría al hacer click
- [ ] **E2:** Persistir filtro en localStorage

---

### 📘 HU-1.3.4: Buscar productos
**Prioridad:** Baja | **Sprint:** 3 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Input de búsqueda en navbar (ícono lupa, estilos, responsive)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Búsqueda en tiempo real (evento `input`)
- [ ] **E2:** Manejar "sin resultados" con mensaje

---

## 📦 FEATURE 1.4: Carrito de Compras

### 📘 HU-1.4.1: Ver carrito de compras
**Prioridad:** Media | **Sprint:** 3 | **Puntos:** 4

#### 🤖 Claude crea:
- [ ] **C1:** Página `cart.html` completa
- [ ] **C2:** Tabla/lista de items (3 mockup, botones +/-, eliminar)
- [ ] **C3:** Card resumen totales (subtotal, envío, total, botón checkout)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Cargar productos desde localStorage y renderizar
- [ ] **E2:** Botones +/- modifican cantidad y actualizan localStorage
- [ ] **E3:** Botón eliminar quita producto (con confirmación)
- [ ] **E4:** Calcular totales automáticamente

---

### 📘 HU-1.4.2: Ver proceso de checkout
**Prioridad:** Baja | **Sprint:** 4 | **Puntos:** 4

#### 🤖 Claude crea:
- [ ] **C1:** Página `checkout.html` (layout 2 columnas)
- [ ] **C2:** Formulario envío (nombre, email, dirección, ciudad, CP)
- [ ] **C3:** Resumen pedido (card fija con productos)
- [ ] **C4:** Botón confirmar (loading state visual)
- [ ] **C5:** Responsive (stack en móvil)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Validar formulario (campos requeridos, formato email, CP numérico)
- [ ] **E2:** Cargar resumen desde localStorage
- [ ] **E3:** Procesar compra simulado (delay, limpiar carrito, redirigir)

---

## 📦 FEATURE 1.5: Contacto

### 📘 HU-1.5.1: Ver página de contacto
**Prioridad:** Baja | **Sprint:** 4 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Página `contact.html` (layout 2 columnas)
- [ ] **C2:** Formulario contacto (nombre, email, asunto, mensaje)
- [ ] **C3:** Info de contacto (email, teléfono, horarios, íconos)
- [ ] **C4:** Responsive

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Validar formulario (email, mensaje min 10 chars)
- [ ] **E2:** Simular envío con mensaje de éxito

---

## 📦 FEATURE 1.6: Responsive Design

### 📘 HU-1.6.1: Asegurar responsive en todo el sitio
**Prioridad:** Alta | **Sprint:** 2 | **Puntos:** 5

#### 🤖 Claude crea:
- [ ] **C1:** Auditar todas las páginas en DevTools
- [ ] **C2:** Ajustar breakpoints Bootstrap
- [ ] **C3:** Optimizar tipografía móvil
- [ ] **C4:** Botones táctiles (min 44x44px)
- [ ] **C5:** Imágenes responsive (max-width 100%)

#### 👨‍💻 Estudiante implementa:
- [ ] **E1:** Testing en dispositivos reales (iPhone, Android)

---

## 📦 FEATURE 1.7: Documentación

### 📘 HU-1.7.1: Documentar componentes
**Prioridad:** Media | **Sprint:** 1 | **Puntos:** 2

#### 🤖 Claude crea:
- [ ] **C1:** Archivo `components.md` (Card, Button, Navbar, Footer con ejemplos)

---

# 📊 RESUMEN

**Total User Stories:** 15  
**Total Tasks Claude:** 42 (UI/Componentes)  
**Total Tasks Estudiante:** 26 (Funcionalidades)  
**Estimación total:** 45 puntos

---

# 🎯 ROADMAP POR SPRINTS

## Sprint 1 (Sem 1-2) - Fundación
**🤖 Claude:** Hero, Productos, About, Navbar, Footer, Docs  
**👨‍💻 Estudiante:** Toggle menu, año dinámico  
**✅ Entregable:** Home completa

## Sprint 2 (Sem 3-4) - Catálogo
**🤖 Claude:** Catalog page, Product detail, Responsive  
**👨‍💻 Estudiante:** Cargar productos, paginación, detalle dinámico, agregar a carrito  
**✅ Entregable:** Catálogo funcional

## Sprint 3 (Sem 5-6) - Carrito
**🤖 Claude:** Filtros, búsqueda, cart page  
**👨‍💻 Estudiante:** Filtrar, buscar, carrito completo (CRUD)  
**✅ Entregable:** Carrito funcional

## Sprint 4 (Sem 7-8) - Cierre
**🤖 Claude:** Checkout, Contact  
**👨‍💻 Estudiante:** Validaciones, checkout simulado, contacto  
**✅ Entregable:** Sitio completo

---

# 📋 DEFINITION OF DONE

**Para Claude (UI):**
- [ ] HTML válido y semántico
- [ ] CSS aplicado con paleta de colores
- [ ] Responsive en móvil/tablet/desktop
- [ ] Hover effects implementados
- [ ] Sin errores en consola

**Para Estudiante (JS):**
- [ ] Funcionalidad implementada según criterios
- [ ] Código comentado
- [ ] Validaciones necesarias aplicadas
- [ ] Testing en Chrome y Firefox
- [ ] Commit con mensaje descriptivo