# HELLENIKA ⚡
### Enciclopedia interactiva de mitología griega y cultura helénica

> *"En el principio era el Mito"*

Una enciclopedia web moderna, bilingüe (ES/EN) y visualmente inmersiva sobre la mitología griega, la cultura helénica y la Grecia antigua. Cada dios tiene su propio tema de color dinámico. Sin frameworks, sin dependencias: HTML + CSS + JS puro.

---

## Demo

🌐 **[Ver en vivo →](https://TU_USUARIO.github.io/hellenika)**

---

## Capturas

*(Añadir screenshots aquí cuando el proyecto esté más avanzado)*

---

## Características

- **12 temas de color dinámicos** — cada uno de los Olímpicos tiene su propia paleta (Zeus: azul+dorado, Poseidón: teal, Hades: púrpura, etc.)
- **Transiciones suaves** entre temas al navegar entre dioses
- **Tipografía clásica** — Cinzel Decorative + Cormorant Garamond
- **Responsive** — funciona en móvil, tablet y escritorio
- **Sin JS en Fase 1** — HTML + CSS puro, accesible y rápido
- **Contenido riguroso** — basado en fuentes primarias (Hesíodo, Homero, Apolodoro)

---

## Estado del proyecto

| Fase | Contenido | Estado |
|------|-----------|--------|
| Fase 1 | HTML + CSS · Landing + Zeus | ✅ En curso |
| Fase 2 | JavaScript · Árbol genealógico · Buscador · Quiz | 🔜 Planificado |
| Fase 3 | Python Flask + SQLite · API REST · Backend | 🔜 Planificado |

### Dioses completados
- [x] Zeus ⚡
- [ ] Hera 👑
- [ ] Poseidón 🔱
- [ ] Atenea 🦉
- [ ] Apolo ☀️
- [ ] Artemisa 🌙
- [ ] Ares ⚔️
- [ ] Afrodita 🌹
- [ ] Hefesto 🔥
- [ ] Hermes 🪽
- [ ] Deméter 🌾
- [ ] Dioniso 🍇

---

## Estructura del proyecto

```
hellenika/
├── index.html          # Landing page — Los 12 Olímpicos
├── css/
│   └── styles.css      # Sistema de temas + estilos globales
├── pages/
│   ├── zeus.html       # ⚡ Zeus — completo
│   ├── hera.html       # 🔜 próximamente
│   └── ...
├── assets/
│   └── (imágenes futuras)
└── README.md
```

---

## Stack tecnológico

**Fase 1 (actual)**
- HTML5 semántico
- CSS3 (variables, grid, flexbox, animaciones, media queries)
- Google Fonts (Cinzel Decorative, Cinzel, Cormorant Garamond)

**Fase 2 (próxima)**
- JavaScript vanilla
- D3.js (árbol genealógico)
- LocalStorage (preferencias)

**Fase 3 (futura)**
- Python 3 + Flask
- SQLite / PostgreSQL
- REST API propia

---

## Instalación local

No requiere instalación ni servidor. Clona y abre en el navegador:

```bash
git clone https://github.com/TU_USUARIO/hellenika.git
cd hellenika
# Abre index.html en tu navegador
```

O con un servidor local simple:

```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .
```

---

## Fuentes y rigor histórico

El contenido se basa en fuentes primarias clásicas:

| Autor | Obra | Época |
|-------|------|-------|
| Hesíodo | Teogonía · Los Trabajos y los Días | ~700 a.C. |
| Homero | Ilíada · Odisea | ~800 a.C. |
| Apolodoro | Bibliotheca | ~100 d.C. |
| Ovidio | Metamorfosis | ~8 d.C. |
| Pausanias | Descripción de Grecia | ~175 d.C. |

---

## Roadmap

- [ ] Completar las 12 páginas de Olímpicos
- [ ] Añadir sección de Titanes (Crono, Rea, Prometeo...)
- [ ] Mapa interactivo del mundo griego antiguo
- [ ] Árbol genealógico interactivo (JS + D3.js)
- [ ] Bestiario (Hidra, Medusa, Cerbero...)
- [ ] Buscador por nombre, tipo o mito
- [ ] Quiz de mitología
- [ ] Calendario helénico con festivales
- [ ] Versión en inglés
- [ ] API REST propia (Flask)

---

## Contribuir

Proyecto personal, pero las sugerencias son bienvenidas. Abre un *issue* si encuentras errores históricos o tienes propuestas de contenido.

---

## Licencia

MIT — libre para uso educativo y personal.

---

*Proyecto desarrollado como parte de mi portfolio de desarrollo web. Estudiante de SMR con pasión por la mitología griega y el desarrollo web.*
