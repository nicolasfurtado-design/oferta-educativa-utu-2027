# Oferta Educativa 2027 • UTU Escuela Técnica Minas

Sitio web oficial de la Oferta Educativa 2027 para la **Escuela Técnica de Minas** (DGETP - UTU / ANEP), departamento de Lavalleja, Uruguay.

Proyecto desarrollado por estudiantes de **2.º año de Bachillerato Tecnológico en Tecnologías de la Información**.

---

## 🚀 Características del Sitio

- **Diseño Responsivo y Moderno:** Adaptado a dispositivos móviles, tablets y ordenadores de escritorio.
- **Catálogo Completo de Cursos:** 19 propuestas educativas organizadas por niveles:
  - Educación Básica Integrada (EBI) - 7.º, 8.º y 9.º Grado.
  - Formación Profesional Básica (FPB) - Mecánica General y Audiovisual.
  - Plan Rumbo (Educación de Adultos).
  - Bachillerato Tecnológico (BT - Plan 2023) - 6 especialidades.
  - Bachillerato Técnico Profesional (BTP - Plan 2022) - 6 especialidades.
  - Educación Superior Terciaria - CTT Gastronomía, Tecnólogo en Administración (UTU-Udelar) y FIT Monitor Deportivo.
- **Páginas de Detalle por Curso:** Perfil de ingreso y egreso, requisitos generales de inscripción y fichas técnicas completas.
- **Página de Contacto e Inscripción:** Formulario con selector de cursos y datos oficiales del centro (dirección, teléfonos, email, Instagram y mapa interactivo).
- **Megamenú Desplegable:** Navegación por categorías sin dependencias externas ni frameworks pesados (HTML5 semántico y CSS3 puro).

---

## 📁 Estructura del Proyecto

```text
├── index.html                           # Portada y catálogo general
├── contacto.html                        # Página de contacto institucional
├── plantillacursos.html                 # Plantilla de referencia para cursos
├── styles.css                           # Hoja de estilos globales
├── img/                                 # Imágenes de stock y fotografías locales
│   ├── ebi-grados.jpg
│   ├── fpb-mecanica-general.jpg
│   └── ... (imágenes locales por curso)
├── ebi-grados.html                      # Páginas individuales de cada curso
├── fpb-mecanica-general.html
├── ... (19 páginas de cursos)
├── server.js                            # Servidor local Node.js para previsualización
├── .nojekyll                            # Compatibilidad con GitHub Pages
└── README.md                            # Documentación del proyecto
```

---

## 🛠️ Visualización Local

Para ver el sitio localmente, puedes simplemente abrir `index.html` con cualquier navegador web o iniciar el servidor estático con Node.js:

```bash
node server.js
```
Luego accede a `http://localhost:8080/`.

---

## 🌐 Publicación en GitHub Pages

Este repositorio está preparado para publicarse directamente con **GitHub Pages**:
1. Ve a **Settings** > **Pages** en este repositorio.
2. En **Build and deployment > Source**, selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/ (root)`.
4. Guarda los cambios. En pocos minutos el sitio estará disponible públicamente en internet con HTTPS gratuito.
