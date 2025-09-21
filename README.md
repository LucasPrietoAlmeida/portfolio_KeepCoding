# 📂 Portfolio – Lucas Prieto

Este es mi **portfolio profesional** desarrollado como parte del Bootcamp de KeepCoding en el módulo **Fundamentos de HTML y CSS3**.  
El proyecto está construido con un enfoque **Mobile First** y es totalmente **responsive**.  

## 🚀 Tecnologías utilizadas

- **HTML5**  
- **CSS3** (con `flexbox`, `grid`, `media queries`)  
- **Normalize.css** para reset de estilos  
- **Mobile First** como metodología  

## 📁 Estructura del proyecto

```
portfolio/
│
├── index.html           # Página principal
├── projects.html        # Página con grid de proyectos
├── video.html           # Página con mockup + vídeo
│
├── styles/
│   ├── normalize.css    # Reset básico
│   ├── style.css        # Estilos principales
│   ├── projects.css     # Estilos específicos para proyectos
│   └── video.css        # Estilos específicos para vídeo
│
├── img/                 # Imágenes (banner, mockups, etc.)
└── video/               # Archivos de vídeo (video.mp4)
```

## 📱 Diseño responsivo

Ejemplos de breakpoints utilizados:  
```css
@media screen and (min-width: 426px) { ... }
```

## ✨ Características principales

- **Página principal (index.html)**  
  - Sección *banner* con imagen adaptada a móvil y desktop.  
  - Sección *sobre mí* con descripción y barras de progreso animadas para skills.  
  - Sección *proyectos destacados* con enlaces a trabajos reales.  
  - Formulario de contacto validado con HTML5.  

- **Página de proyectos (projects.html)**  
  - Grid responsivo con tarjetas de proyectos.  
  - Cada tarjeta incluye título, descripción y enlace.  

- **Página de vídeo (video.html)**  
  - Vídeo incrustado dentro de un mockup de móvil con animación `fadeIn`.  

## 🎨 Paleta de colores

```css
:root {
    --bg-color: #F5F3F0;
    --primary-brand-color: #D8CFC4;
    --secondary-brand-color: #CEC6BE;
    --accent-color: #B6771A;
    --main-text-color: #3D3A36;
}
```

## 🧪 Cómo probar el proyecto

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/TU_USUARIO/portfolio.git
   ```
2. Abrir `index.html` en el navegador.  
3. Navegar entre las páginas usando el menú.  


## 👨‍💻 Autor

**Lucas Prieto Almeida**  
- [GitHub](https://github.com/LucasPrietoAlmeida)  
- [LinkedIn](https://www.linkedin.com/in/lucas-prieto-almeida/)  
