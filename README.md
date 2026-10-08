# 🌿 RIDM - Plataforma Web Corporativa & Identidad de Marca

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Live](https://img.shields.io/badge/Demo-Live-4CAF50?style=flat)](https://recolectoraintegral.com.mx/)
[![Status](https://img.shields.io/badge/Status-Produccion-success?style=flat)]()

> **Solución web integral para Recolectora Integral de Desechos de México: sitio corporativo, identidad de marca y materiales comerciales. Un caso real de digitalización de procesos empresariales.**

🔗 **[🚀 Ver Sitio en Vivo](https://recolectoraintegral.com.mx/)** | 📂 **[Ver Brochure](#-material-grafico-complementario)**

---

## 📖 Sobre el Proyecto

**Recolectora Integral de Desechos de México (RIDM)** es una empresa de gestión de residuos con cobertura en CDMX, Estado de México, Hidalgo, Morelos y Querétaro. 

### 🎯 El Desafío
RIDM necesitaba:
- **Digitalizar su presencia** para alcanzar clientes corporativos (B2B).
- **Comunicar profesionalmente** sus servicios de recolección y reciclaje.
- **Fortalecer su identidad de marca** en un mercado competitivo.
- **Automatizar la captación de leads** mediante herramientas digitales.

### 💡 La Solución
Desarrollé una **plataforma web corporativa completa** que incluye:
- ✅ Sitio web responsive de alto rendimiento (arquitectura monolítica optimizada).
- ✅ Identidad visual completa (logo, paleta, tipografía).
- ✅ Mascota corporativa "RIDM" (economía circular humanizada).
- ✅ Brochure digital interactivo para ventas B2B.
- ✅ Dominio personalizado: `recolectoraintegral.com.mx`.

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnologías |
| :--- | :--- |
| **Frontend** | HTML5 (semántico), CSS3 (interno/responsive), JavaScript (ES6+ interno) |
| **Diseño** | Google Fonts (Montserrat/Roboto), CSS Grid/Flexbox |
| **Optimización** | Single-file architecture (menor latencia, 1 sola petición HTTP inicial) |
| **Hosting** | Servidor web con dominio personalizado |
| **Control de Versiones** | Git, GitHub |

---

## ✨ Características del Sitio Web

### 🏗️ **Arquitectura de Información**
El sitio incluye 10 secciones estratégicas diseñadas para conversión:
1. **Inicio** — Hero section con propuesta de valor clara.
2. **Nosotros** — Historia y valores de la empresa.
3. **Por Qué Elegirnos** — Diferenciadores competitivos.
4. **Servicios** — Catálogo completo de recolección y gestión.
5. **Cómo Trabajamos** — Proceso paso a paso (transparencia).
6. **Materiales** — Tipos de residuos que gestionan.
7. **Sostenibilidad Creativa** — Iniciativas de arte y reutilización.
8. **ECOShop** — Tienda de productos sustentables.
9. **Cobertura** — Mapa de zonas de servicio.
10. **Contacto** — Formulario + datos directos (multi-canal).

### 📱 **Responsive Design**
- Mobile-first approach.
- Breakpoints optimizados para móviles, tablets y desktop.
- Navegación táctil optimizada.

---

## 🎨 Identidad Visual y Branding

### 🦝 Mascota Corporativa "RIDM"
Desarrollé una eco-mascota que representa los valores de la empresa:
- **Concepto:** Economía circular personificada.
- **Objetivo:** Humanizar la marca y generar cercanía emocional.
- **Público:** Clientes B2B y B2C (empresas y hogares).
- **Mensaje:** "La Confianza de Nuestros Clientes Nos Respalda".
- **Aplicaciones:** Web, redes sociales, eventos, reciclatones.

### 📄 Brochure Digital Interactivo
Pieza comercial de alto impacto para ventas B2B:
- **Formato:** Diseño visual de alto impacto.
- **Estrategia:** Dolor → Solución → Prueba → Acción.
- **CTA Principal:** "Solicita tu diagnóstico gratuito".

### 🎨 Sistema de Diseño
| Elemento | Especificación |
| :--- | :--- |
| **Color Principal** | `#2D8A3E` (Verde ambiental) |
| **Color Secundario** | `#1A5C26` (Verde corporativo) |
| **Acento** | `#FFFFFF` (Blanco limpio) |
| **Fondo** | `#F5F5F5` (Gris claro) |
| **Tipografía** | Montserrat / Roboto (Sans-serif moderna) |
| **Estilo** | Profesional, ambiental, corporativo, limpio |

---

## 📂 Estructura del Proyecto

El proyecto utiliza una **arquitectura monolítica optimizada** para el frontend, centralizando la lógica y los estilos para máxima portabilidad y velocidad de carga inicial:

```text
ridm/
├── index.html              # 🏠 Sitio web completo (HTML + CSS interno + JS interno)
├── assets/                 # 📁 Recursos externos
│   ├── images/             # Imágenes optimizadas (logos, fotos, mascota)
│   └── brochure/           # Material comercial (Brochure.png)
└── README.md               # 📄 Este archivo
```

---

## ⚙️ Cómo Ejecutar el Proyecto

### Opción 1: Ver en Vivo (Recomendado)
Visita: **[https://recolectoraintegral.com.mx/](https://recolectoraintegral.com.mx/)**

### Opción 2: Ejecutar Localmente
```bash
# 1. Clona el repositorio
git clone https://github.com/JULIO-MILAN/ridm.git
cd ridm

# 2. Abre index.html directamente en tu navegador con doble clic
# (O usa la extension "Live Server" en VS Code para recarga automatica)
```
*Nota: Gracias a su arquitectura autocontenida, no requiere instalación de dependencias (npm), ni compilación, ni servidor backend para su visualización.*

---

## 🧠 Retos de Ingeniería y Soluciones

### 1️⃣ **Rendimiento y Portabilidad (Single-File Architecture)**
- **Reto:** Garantizar que el sitio cargue instantáneamente y sea fácil de desplegar o mover entre servidores sin romper rutas relativas.
- **Solución:** Centralización de CSS y JS dentro del `index.html`. Esto reduce las peticiones HTTP iniciales a 1, mejorando el *First Contentful Paint* (FCP) y haciendo el sitio 100% portable.
- **Aprendizaje:** A veces, la simplicidad arquitectónica (monolito frontend) es la solución más robusta para landing pages corporativas.

### 2️⃣ **Diseño Responsive sin Frameworks Pesados**
- **Reto:** Crear un sitio de 10 secciones que se vea perfecto en todos los dispositivos sin depender de Bootstrap o Tailwind.
- **Solución:** Implementación de CSS Grid y Flexbox con media queries personalizadas, enfoque mobile-first.
- **Aprendizaje:** Dominio profundo de CSS layout systems nativos sin muletas externas.

### 3️⃣ **Identidad Visual desde Cero**
- **Reto:** Crear una marca completa que comunique profesionalismo y sostenibilidad.
- **Solución:** Investigación, diseño iterativo y creación de una mascota que humanice el servicio B2B/B2C.
- **Aprendizaje:** El diseño es comunicación estratégica de valores, no solo estética.

### 4️⃣ **Arquitectura de Información para Conversión**
- **Reto:** Estructurar el contenido para guiar al visitante desde el conocimiento hasta el contacto.
- **Solución:** Diseño de user journey: Hero → Servicios → Diferenciadores → Testimonios → CTA claro.
- **Aprendizaje:** Un sitio web empresarial es una herramienta activa de ventas.

---

## 🚀 Próximos Pasos y Mejoras Futuras

1. **Modularización:** Si el sitio escala a más de 15 páginas, migrar a una arquitectura con archivos CSS/JS separados o un generador de sitios estáticos (Astro/Next.js).
2. **Backend para ECOShop:** Implementar carrito de compras funcional con pasarela de pagos.
3. **CMS para Autoadministración:** Integrar un headless CMS para que el cliente pueda actualizar servicios sin tocar código.
4. **Formulario con Backend:** Conectar el formulario de contacto a un servicio como Formspree o backend propio con Node.js.
5. **Analytics:** Implementar Google Analytics 4 para tracking de conversiones y comportamiento de usuarios.

---

## 📊 Capturas de Pantalla

<details>
<summary><b>🖼️ Click para ver galería</b></summary>
<br>

<table>
<tr>
<td align="center">
<b>Brochure / Material Visual</b><br><br>
<img src="https://github.com/user-attachments/assets/8a7d113e-2ef4-47db-9e1d-7528b1554dae" width="400">
</td>

<td align="center">
<b>Mascota Corporativa RIDM</b><br><br>
<img src="https://github.com/user-attachments/assets/b75b2b03-9c17-40c9-a995-8e5308574b45" width="400">
</td>
</tr>
</table>

</details>

---

## 👥 Información del Proyecto

### 🏢 Cliente
| | |
| :--- | :--- |
| **Empresa** | Recolectora Integral de Desechos de México (RIDM) |
| **Contacto** | Lic. Karla Maturano Dotor |
| **Cargo** | Gerente de Desarrollo de Proyectos y Negocios |
| **Cobertura** | CDMX · Edo. México · Hidalgo · Morelos · Querétaro |
| **Industria** | Gestión de Residuos y Reciclaje |

### 👨‍💻 Desarrollador
| | |
| :--- | :--- |
| **Nombre** | Julio Adrian Milan Huidobro |
| **Rol** | Full Stack Web Developer & Diseñador UX/UI |
| **Email** | [milan.ewok@gmail.com](mailto:milan.ewok@gmail.com) |
| **GitHub** | [JULIO-MILAN](https://github.com/JULIO-MILAN) |

---

## 💡 Conclusión Técnica y de Negocio

Este proyecto demuestra **capacidad de crear soluciones integrales a problemas reales de negocio**:

- **No es solo código:** Incluye branding, identidad visual, estrategia de comunicación y materiales comerciales.
- **No es solo un sitio web:** Es una herramienta de captación de leads y posicionamiento de marca.
- **No es solo diseño:** Es arquitectura de información pensada en conversión y experiencia de usuario.

**Impacto Real:** RIDM ahora tiene presencia digital profesional, puede competir en licitaciones corporativas y cuenta con herramientas para automatizar su proceso de ventas.

> *"De la necesidad de digitalizar una empresa tradicional, nació una solución completa que combina desarrollo web, diseño de marca y estrategia comercial."*

---

<div align="center">
 
**RIDM — Soluciones Integrales** ♻️  
*Comprometidos con soluciones ambientales responsables*

[🌐 Visitar Sitio Web](https://recolectoraintegral.com.mx/)
</div>
