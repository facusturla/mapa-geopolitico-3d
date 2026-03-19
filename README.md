# Mapa Geopolítico 3D

Este mapa interactivo permite visualizar y analizar los principales bloques económicos, alianzas militares y acuerdos de defensa a nivel mundial.

Fue diseñado para ofrecer un panorama geopolítico rápido, destacando qué países pertenecen a organizaciones clave (como la OTAN, los BRICS+, la Unión Europea, etc.) y mapeando tratados de defensa bilaterales y multilaterales.

## Características

* **Visualización 3D:** El globo terráqueo es completamente interactivo. Podés rotarlo, hacer zoom y seleccionar cualquier país para ver su ficha en el panel lateral.
* **Filtros rápidos:** Permite segmentar el mapa entre bloques Económicos, Militares o Acuerdos de Defensa particulares.
* **Foco en Argentina:** Incluye una vista dedicada que resalta a los países con los que Argentina mantiene acuerdos de defensa vigentes, mostrando el nombre oficial de cada tratado.
* **Portabilidad total:** Toda la base de datos y la geometría de los países está pre-compilada dentro del archivo HTML principal.

## Cómo probarlo

Para abrirlo o compartirlo no se necesita instalar absolutamente nada ni levantar un servidor local. 

Con hacerle doble clic al archivo `index.html` para que se abra en el navegador web (Chrome, Edge, Firefox) alcanza. Al ser un desarrollo autocontenido, le podés mandar el HTML a cualquier persona por mail o WhatsApp y le va a funcionar directo sin romperse.

## Stack técnico

* **Globe.gl** y **Three.js** corriendo sobre WebGL para el motor 3D.
* Interfaz construida con HTML5, CSS3 y Vanilla JavaScript puro. 
* Los datos de polígonos (GeoJSON) y atributos lógicos están incrustados directamente dentro de las constantes JS para garantizar el funcionamiento offline y evitar bloqueos de CORS.
