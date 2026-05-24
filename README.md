# 🛒 Desafío 2 - Layout de E-commerce con Grid

---

## 🌐 Demo del proyecto

<p align="center">
  <a href="https://jleival.github.io/desafio-2-layout-de-e_commerce-con-grid/">
    <img src="https://img.shields.io/badge/🔗_Ver_Demo-GitHub_Pages-2ea44f?style=for-the-badge" />
  </a>
</p>

<p align="center">
  <a href="https://jleival.github.io/desafio-2-layout-de-e_commerce-con-grid/">
    <img 
      src="https://raw.githubusercontent.com/jleival/desafio-2-layout-de-e_commerce-con-grid/main/assets/img/preview.png" 
      alt="Preview del proyecto"
      width="900"
    >
  </a>
</p>

---

## 📌 Descripción

Este proyecto consiste en el desarrollo de una tienda online responsiva utilizando HTML5, CSS Grid y Flexbox. El objetivo principal es construir un layout moderno y organizado aplicando buenas prácticas de maquetación web.

La interfaz incluye:

* Encabezado principal.
* Barra lateral con categorías.
* Grilla de productos.
* Tarjetas de productos.
* Pie de página.

El desafío fue desarrollado siguiendo los requerimientos solicitados para reforzar el uso de CSS Grid en la creación de layouts y Flexbox en la alineación de componentes.

---

## 🚀 Tecnologías utilizadas
* HTML5
* CSS3
* CSS Grid
* Flexbox
* Normalize.css

---

## 🎯 Objetivos del desafío
* Implementar un layout utilizando grid-template-areas.
* Construir una grilla de productos con CSS Grid.
* Utilizar Flexbox para distribuir elementos en la barra lateral.
* Crear tarjetas de productos utilizando Flexbox.
* Aplicar diseño responsivo y estructura semántica.

---

## ## 🖥️ Estructura del Layout

| Sección | Descripción |
|----------|-------------|
| Header | Encabezado principal del e-commerce |
| Sidebar | Menú lateral con categorías y cantidad de productos |
| Main | Contenedor principal de productos |
| Productos | Grilla de tarjetas de productos |
| Footer | Pie de página del sitio |

---

## 📌 Descripción

Este proyecto consiste en el desarrollo de una tienda online responsiva utilizando **HTML5**, **CSS Grid** y **Flexbox**. El objetivo principal es construir un layout moderno y organizado aplicando buenas prácticas de maquetación web.

La interfaz incluye:

* Encabezado principal.
* Barra lateral con categorías.
* Grilla de productos.
* Tarjetas de productos.
* Pie de página.

El desafío fue desarrollado siguiendo los requerimientos solicitados para reforzar el uso de **CSS Grid** en la creación de layouts y **Flexbox** en la alineación de componentes.

---

## 🚀 Tecnologías utilizadas

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Normalize.css

---

## 🎯 Objetivos del desafío

* Implementar un layout utilizando `grid-template-areas`.
* Construir una grilla de productos con CSS Grid.
* Utilizar Flexbox para distribuir elementos en la barra lateral.
* Crear tarjetas de productos utilizando Flexbox.
* Aplicar diseño responsivo y estructura semántica.

---

## 🖥️ Estructura del Layout

El proyecto está compuesto por las siguientes secciones:

| Sección   | Descripción                                         |
| --------- | --------------------------------------------------- |
| Header    | Encabezado principal del e-commerce                 |
| Sidebar   | Menú lateral con categorías y cantidad de productos |
| Main      | Contenedor principal de productos                   |
| Productos | Grilla de tarjetas de productos                     |
| Footer    | Pie de página del sitio                             |

---

## 📂 Estructura del proyecto

```bash
.
├── index.html
├── assets
│   ├── css
│   │   ├── normalize.css
│   │   └── style.css
│   └── img
│       ├── articulo_1.png
│       ├── articulo_2.png
│       ├── articulo_3.png
│       └── articulo_4.png
```

---

## 🧩 Implementación CSS Grid

El layout principal fue construido utilizando:

```css
.grid-container {
  display: grid;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
}
```

Esto permite organizar visualmente cada sección del sitio de forma clara y escalable.

---

## 📦 Implementación de la grilla de productos

La sección de productos utiliza CSS Grid para distribuir las tarjetas:

```css
.productos {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

---

## 🎨 Uso de Flexbox

Flexbox fue utilizado en:

* Distribución de elementos del sidebar.
* Alineación del contenido de las tarjetas.
* Posicionamiento de botones.
* Centrado de elementos.

Ejemplo:

```css
.tarjeta {
  display: flex;
  flex-direction: column;
  align-items: center;
}
```

---

## 🛍️ Productos incluidos

* Perfume myKingdom
* Perfume Phantom
* Zapatos Docker
* Polerón Puma

---

## 📸 Características del proyecto

✅ Layout responsivo.

✅ Uso de Grid Template Areas.

✅ Tarjetas organizadas con Flexbox.

✅ Diseño limpio y estructurado.

✅ Navegación lateral de categorías.

✅ Uso de Normalize.css.

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/jleival/desafio-2-layout-de-e_commerce-con-grid.git
```

2. Abrir el proyecto en Visual Studio Code.

3. Ejecutar con Live Server o abrir el archivo `index.html` en el navegador.

---

## 📚 Aprendizajes obtenidos

Durante el desarrollo del desafío se reforzaron conocimientos relacionados con:

* Maquetación web moderna.
* Distribución avanzada con CSS Grid.
* Organización visual mediante Flexbox.
* Diseño responsivo.
* Estructura semántica HTML.
* Buenas prácticas de estilos CSS.

---

## 👨‍💻 Autor

	                   Jorge Leiva
Proyecto desarrollado para **Desafío-Latam** como parte del proceso de aprendizaje y fortalecimiento de habilidades en maquetación web moderna utilizando HTML5, CSS Grid y Flexbox.
