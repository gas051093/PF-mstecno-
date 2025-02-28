# MsTecno

**MsTecno** es una empresa ficticia dedicada a brindar servicios de sonido, iluminación y alquiler de pantallas LED para eventos. Este proyecto forma parte del curso de Desarrollo Web dentro de la carrera Fullstack en Coderhouse.

### Autor
**Gaston Mgrassi**

---

## ✨ Tecnologías utilizadas

- **HTML5**
- **CSS3 (SASS)**
- **Bootstrap** (Se utilizo para sistemas de grilla y componentes)
- **Open Graph** (para mejorar la previsualización en redes sociales)

---
## 🎨 Estilos

El proyecto utiliza **Sass** con una estructura modular, organizando estilos en:
- `_layouts/` → Secciones principales.
- `_mixins/` → Animaciones y efectos.
- `_variables/` → Paleta de colores y configuraciones.

---
## 📸 Optimización de Imágenes

Las imágenes están en formato **WebP**, optimizando el rendimiento en la web.

---

## 📂 Estructura del proyecto

```
|   index.html
|   package.json
|   README.md
|
+---assets
|   \---img
|           contacto.webp
|           hero-galeria.webp
|           hero.webp
|           img01.webp
|           img02.webp
|           img03.webp
|           img04.webp
|           img_og.jpg
|           logo.ico
|           logo_empresa.png
|           nosotros.webp
|
+---html
|       contacto.html
|       galeria.html
|
+---sass
|   |   style.scss
|   |
|   +---layouts
|   |       _about.scss
|   |       _contact.scss
|   |       _foot.scss
|   |       _galery.scss
|   |       _hero.scss
|   |       _navbar.scss
|   |
|   +---mixins
|   |       _animations.scss
|   |       _hoverfx.scss
|   |
|   \---variable
|           _colors.scss
|           _mq.scss
|           _reset.scss
|
\---styles
        main.css
        main.css.map
```

---

## 📝 Instalación y uso

1. Clonar el repositorio:
```bash
git clone https://github.com/gas051093/PF-mstecno-.git
```
2. Ingresar al proyecto:
```bash
cd PF-mstecno-
```
3. Instalar dependencias (si las hubiera):
```bash
npm install
```
4. Compilar SASS (en caso de realizar cambios):
```bash
npm run sass
```
5. Abrir `index.html` en el navegador o utilizar Live Server.

---

## 🔄 Mejoras futuras
- Implementación de un formulario de contacto con validaciones en JavaScript.
- Mejorar la performande de cada html

---

👉 **Repositorio en GitHub:** [MsTecno](https://github.com/gas051093/PF-mstecno-)

👉 **Deploy:** [Ver online](https://mstecno.netlify.app/)

