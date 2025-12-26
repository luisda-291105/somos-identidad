# 🧢 SOMOS IDENTIDAD

<div align="center">

![Project Status](https://img.shields.io/badge/status-in%20development-blue)
![Phase](https://img.shields.io/badge/phase-frontend-brightgreen)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

**Una distribuidora de ropa básica, moderna y cómoda para tu día a día**

[Ver Demo](#) · [Reportar Bug](#) · [Solicitar Feature](#)

</div>

---

## 📖 Sobre el Proyecto / About the Project

**SOMOS IDENTIDAD** es un proyecto académico que simula una **distribuidora de ropa** enfocada en prendas básicas y cómodas para el uso diario. 

> 💡 **Concepto:** Cada persona elige su ropa según su forma de vivir, sin seguir modas exageradas. Tu identidad, tu estilo.

### 🎯 Propósito

Este proyecto sirve como base de aprendizaje para:
- ✅ Entender cómo funciona una tienda de ropa online
- ✅ Aprender arquitectura limpia y modular
- ✅ Gestionar productos, inventario y ventas
- ✅ Practicar lógica de negocio en un entorno real
- ✅ Desarrollar buenas prácticas de desarrollo web

---

## 🚀 ¿Qué hace SOMOS IDENTIDAD?

SOMOS IDENTIDAD **NO fabrica** ropa. Somos una **distribuidora** que:
- 📦 Organiza productos de diferentes proveedores
- 👕 Muestra catálogo de prendas básicas
- 🛒 Gestiona inventario y stock
- 💳 Simula proceso de compra

---

## 🏗️ Arquitectura del Proyecto

### Desarrollo por Fases

```
┌─────────────────────────────────────────────────┐
│  FASE 1: FRONTEND (Actual)                      │
│  ├── Bootstrap 5 (sin JavaScript)               │
│  ├── Componentes reutilizables                  │
│  └── UI/UX minimalista                          │
├─────────────────────────────────────────────────┤
│  FASE 2: BACKEND (Próximamente)                 │
│  ├── Lógica de negocio                          │
│  ├── Gestión de inventario                      │
│  └── Procesamiento de pedidos                   │
├─────────────────────────────────────────────────┤
│  FASE 3: BASE DE DATOS (Futuro)                 │
│  ├── Persistencia de datos                      │
│  ├── Gestión de usuarios                        │
│  └── Historial de compras                       │
└─────────────────────────────────────────────────┘
```

### Desarrollo Modular

El proyecto crece por módulos independientes:

1. **Módulo 1:** Camisetas básicas *(actual)*
2. **Módulo 2:** Gorras y accesorios
3. **Módulo 3:** Pantalones y bottoms
4. **Módulo N:** Expansión según necesidad

---

## 🎨 Design System

### Paleta de Colores

```css
/* Primary - Azul vibrante */
#3b82f6  #2563eb  #60a5fa

/* Dark Backgrounds - Fondos oscuros */
#0a0e27  #1a1d3a  rgba(20, 25, 45, 0.9)

/* Text - Textos claros */
#f8fafc  #cbd5e1  #e2e8f0

/* Accent - Cyan brillante */
#06b6d4  #22d3ee  #67e8f9
```

### Principios de Diseño

- 🎯 **Minimalista:** Sin elementos innecesarios
- ✨ **Fresco:** Colores vibrantes y modernos
- 🌙 **Dark Mode:** Diseño oscuro principal
- 💎 **Premium:** Glassmorphism y transparencias
- 📱 **Responsive:** Mobile-first approach

---

## 📁 Estructura del Proyecto

```
somos-identidad/
│
├── 📄 index.html                 # Página principal
│
├── 📂 pages/                     # Páginas del sitio
│   ├── catalog.html              # Catálogo de productos
│   ├── product-detail.html       # Detalle de producto
│   ├── cart.html                 # Carrito de compras
│   ├── checkout.html             # Proceso de compra
│   └── contact.html              # Contacto e información
│
├── 📂 assets/                    # Recursos estáticos
│   ├── css/
│   │   └── custom-styles.css     # Estilos personalizados
│   └── images/                   # Imágenes del proyecto
│
└── 📂 docs/                      # Documentación
    ├── architecture.md           # Arquitectura del proyecto
    ├── components.md             # Documentación de componentes
    └── style-guide.md            # Guía de estilo
```

---

## 🛠️ Stack Tecnológico

### Fase Actual: Frontend

| Tecnología | Versión | Uso |
|------------|---------|-----|
| HTML5 | - | Estructura semántica |
| CSS3 | - | Estilos personalizados |
| Bootstrap | 5.3 | Framework UI |

### Próximas Fases

- **Backend:** Por definir (Node.js, Python, Java)
- **Base de datos:** Por definir (MySQL, MongoDB, PostgreSQL)

---

## ✨ Funcionalidades

### ✅ Implementadas (Fase Frontend)

- [x] Componentes de producto (cards)
- [x] Sistema de diseño consistente
- [x] Paleta de colores definida
- [ ] Navbar responsive
- [ ] Catálogo de productos
- [ ] Filtros y búsqueda
- [ ] Detalle de producto
- [ ] Carrito de compras (UI)

### 🔜 Por Implementar

- [ ] Gestión de inventario (Backend)
- [ ] Sistema de usuarios (Backend)
- [ ] Procesamiento de pedidos (Backend)
- [ ] Base de datos (DB)
- [ ] Pasarela de pago simulada

---

## 🎓 Metodología de Aprendizaje

Este proyecto sigue un enfoque educativo estructurado:

### Los 5 Roles del Desarrollo

1. **👨‍🎨 Diseñador:** Crea componentes con Bootstrap
2. **👨‍🏫 Profesor:** Explica conceptos sin código
3. **🐛 Debugger:** Identifica y soluciona errores
4. **📝 Documentador:** Genera documentación necesaria
5. **📊 Evaluador:** Revisa organización del proyecto

### Principios de Aprendizaje

- 🧠 **Progresivo:** De básico a avanzado
- 🔁 **Iterativo:** Mejora continua
- 🎯 **Práctico:** Aprender haciendo
- 📚 **Documentado:** Todo está explicado
- 🤝 **Colaborativo:** Feedback constante

---

## 🚦 Cómo Empezar

### Prerrequisitos

- Navegador web moderno
- Editor de código (VS Code recomendado)
- Git instalado

### Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/tuusuario/somos-identidad.git

# 2. Entrar al directorio
cd somos-identidad

# 3. Abrir en el navegador
# Simplemente abre index.html en tu navegador
```

### Desarrollo Local

```bash
# Si tienes Python instalado
python -m http.server 8000

# Si tienes Node.js instalado
npx http-server

# Luego visita: http://localhost:8000
```

---

## 📝 Convenciones del Proyecto

### Nomenclatura

```
camelCase       → Variables y funciones JS
kebab-case      → Archivos y clases CSS
PascalCase      → Componentes React (futuro)
UPPER_CASE      → Constantes
```

### Commits

```
feat: nueva funcionalidad
fix: corrección de bug
docs: cambios en documentación
style: cambios de formato (sin afectar código)
refactor: refactorización de código
test: agregar o modificar tests
```

### Idioma

- **Código:** Inglés (variables, funciones, clases)
- **Comentarios:** Español/Inglés mixto
- **Documentación:** Bilingüe
- **UI:** Español

---

## 🤝 Contribuir

Este es un proyecto de aprendizaje personal, pero sugerencias y feedback son bienvenidos:

1. 🍴 Fork el proyecto
2. 🌱 Crea tu rama (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit tus cambios (`git commit -m 'feat: Add AmazingFeature'`)
4. 📤 Push a la rama (`git push origin feature/AmazingFeature`)
5. 🎉 Abre un Pull Request

---

## 📚 Recursos de Aprendizaje

- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/)
- [HTML5 MDN Web Docs](https://developer.mozilla.org/es/docs/Web/HTML)
- [CSS3 MDN Web Docs](https://developer.mozilla.org/es/docs/Web/CSS)
- [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

---

## 📊 Estado del Proyecto

```
Progreso General:  ████░░░░░░ 40%

Frontend:          ███████░░░ 70%
Backend:           ░░░░░░░░░░  0%
Base de Datos:     ░░░░░░░░░░  0%
Documentación:     █████░░░░░ 50%
```

---

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---

## 👤 Autor

**Estudiante de Desarrollo de Software**
- Semestre: 2do
- Proyecto: Académico
- Estado: En desarrollo activo

---

## 💬 Contacto

¿Preguntas o sugerencias sobre el proyecto?

- 📧 Email: [tu-email@example.com]
- 💼 LinkedIn: [Tu perfil]
- 🐙 GitHub: [@tuusuario]

---

## 🙏 Agradecimientos

- Bootstrap por el framework UI
- La comunidad de desarrolladores
- Recursos educativos online
- Mentores y profesores

---

<div align="center">

**⭐ Si este proyecto te ayuda a aprender, considera darle una estrella**

---

Hecho con ❤️ y mucho ☕ para aprender desarrollo web

**SOMOS IDENTIDAD** - Tu identidad, tu estilo

</div>