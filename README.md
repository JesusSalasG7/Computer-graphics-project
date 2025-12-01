# 🔦 La Sombra del Espejo

**Proyecto de Entorno de Computación Gráfica en Unreal Engine 5.1.1**

[![GitHub](https://img.shields.io/badge/Versi%C3%B3n%20UE-5.1.1-blue)](https://www.unrealengine.com/)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-green)](LICENSE)

## 📜 Descripción del Proyecto

**La Sombra del Espejo** es un proyecto de visualización en tiempo real y *walkthrough* interactivo, desarrollado en **Unreal Engine 5.1.1**. El proyecto se enfoca en crear una atmósfera de misterio y detalle a través de un salón gótico/antiguo, utilizando las tecnologías de renderizado de última generación de Unreal Engine 5.

### Objetivos Clave:

* **Dominio de Renderizado:** Demostrar el uso avanzado de **Lumen** (Iluminación Global y Reflejos) y **Nanite** (Geometría de alta densidad) para lograr un realismo extremo en tiempo real.
* **Diseño de Iluminación:** Crear una narrativa visual a través de la iluminación volumétrica y el *light baking* dinámico.
* **Optimización:** Asegurar un rendimiento jugable (frame rate) manteniendo la fidelidad visual.

---

## ✨ Características Técnicas

* **Nanite:** Utilizado para toda la geometría de alta complejidad (paredes, esculturas, props principales).
* **Lumen:** Implementación completa para la iluminación global, reflejos de *software* y oclusión ambiental en tiempo real.
* **Materiales PBR:** Uso de *Materiales Maestros* modulares que facilitan la creación de instancias con ajustes de suciedad, desgaste y propiedades de reflexión.
* **Efectos Cinematográficos:** Volumen de Post-Procesado configurado con *LUT* (Look Up Table), *Screen Space Global Illumination* (SSGI) y profundidad de campo (*Depth of Field*).

---

## 🛠️ Requisitos del Sistema

Este proyecto es demandante debido al uso intensivo de Lumen y Nanite.

| Componente | Mínimo Recomendado |
| :--- | :--- |
| **Motor Gráfico** | **Unreal Engine 5.1.1** |
| **Sistema Operativo** | Windows 10/11 (64-bit) |
| **Procesador** | Intel Core i7 (9th Gen) / AMD Ryzen 7 |
| **Memoria RAM** | 32 GB |
| **Tarjeta Gráfica** | NVIDIA GeForce RTX 3060 / AMD Radeon RX 6700 |
| **Almacenamiento** | 70 GB (SSD NVMe muy recomendado) |

---

## 🚀 Instalación y Ejecución

Todos los *assets*, *shaders* y la configuración del proyecto están incluidos en esta carpeta.

1.  **Descargar el Proyecto:** Clona este repositorio o descarga el archivo ZIP completo.
2.  **Verificar la Versión:** Asegúrate de tener **Unreal Engine 5.1.1** instalado a través del Epic Games Launcher.
3.  **Abrir el Proyecto:** Navega hasta la carpeta raíz del proyecto y abre el archivo **`LaSombraDelEspejo.uproject`**.
4.  **Carga Inicial:** El motor puede tardar unos minutos en cargar el contenido y compilar los *shaders* la primera vez.
5.  **Abrir Nivel:** Una vez en el editor, abre el nivel principal ubicado en `Content/Maps/Nivel_Principal.umap`.
6.  **Ejecutar:** Presiona el botón **Play** (▶️) en la barra de herramientas.

### Controles de Walkthrough

| Acción | Tecla |
| :--- | :--- |
| **Mover Adelante** | W |
| **Mover Atrás** | S |
| **Mover Izquierda** | A |
| **Mover Derecha** | D |
| **Mirar/Girar** | Movimiento del Mouse |

---

## 📦 Estructura de Assets Incluidos

Todo el contenido utilizado es original o está licenciado para uso en este proyecto de portafolio/demostración.

| Carpeta | Descripción | Fuente del Contenido |
| :--- | :--- | :--- |
| `Content/Geometry` | Mallas estáticas (Nanite) para arquitectura y estructuras. | Modelado Propio (Blender/Maya) |
| `Content/Props` | Accesorios, mobiliario, candelabros y espejos. | Modelado Propio y Quixel Megascans |
| `Content/Materials` | Materiales Maestros, Instancias y Funciones de Material. | Creación Propia |
| `Content/Textures` | Mapas Albedo, Normal, Roughness, etc. (4K-8K). | Adobe Substance Painter/Quixel |
| `Content/Blueprints` | Blueprints para el personaje, luces interactivas y efectos. | Creación Propia |
| `Content/FX` | Sistemas de partículas de humo y polvo ambiental. | Creación Propia |

---

## 🖼️ Galería y Demostración

[Añadir un GIF o una imagen que muestre el entorno en movimiento aquí]

[Añadir una captura de pantalla del detalle de Nanite aquí]

---

## 🤝 Autor

**Desarrollado por:** [Tu Nombre Completo / Nombre del Estudio]

**Contacto:** [Tu Correo Electrónico] | [Tu Perfil de LinkedIn] | [Tu Portafolio]

## ⚖️ Lic
