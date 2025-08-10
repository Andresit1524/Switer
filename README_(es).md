# Switer (a.k.a. SwiterMD)
> *Escritura de calidad para todos*

**Switer** (o *SwiterMD* como desambiguación) es un editor de texto *en desarrollo* orientado a la escritura, notas y PKM (*Gestión Personal del Conocimiento*), que busca destacar por la comodidad, la potencia y la simplicidad.

## Características principales *planeadas*
- Editor Markdown con capacidad de edición WYSIWYG y vista previa
- Edición por bloques más capaz y dinámica para una experiencia más fluida
- Una variante de Markdown propia diseñada para ser más compatible, elegante y portable
- Integración con extensiones como LaTeX, Mermaid, embeds y referencias cruzadas
- Máximo rendimiento y velocidad de uso
- Diseño mejorado para dispositivos móviles y de escritorio
- Local-first, sin login, solo archivos locales en tu disco
- Sistema de plugins base y posibilidad de plugins de terceros
- Aspecto elegante, limpio y dinámico
- Integraciones con terceros, sincronización y mejores capacidades de exportación

Y lo más importante: **no busca imitar los errores de los programas de su tipo**. Switer nace de la necesidad de una aplicación capaz y apta para todos, a diferencia de los programas actuales, muy técnicos e **incompletos**.

### Filosofía
Switer busca cumplir con los siguientes principios:

1. **Rápido:** en rendimiento gracias a su stack Svelte + Tauri, pero también en experiencia y uso.
2. **Cómodo:** que escribir sea un proceso libre sin fricciones, sin inconvenientes y con la mejor accesibilidad posible.
3. **Elegante:** sin incomodidades, sin soluciones a medias. Un espacio con todo lo necesario con un diseño bien pensado.
4. **Completo:** que cada función este en cada versión. Nada de versiones restringidas en funciones, recortes o limitaciones.
5. **Portable:** sean versiones portables y multiplataforma, con capacidades de exportación y acceso a tus notas, Switer no es una forma de dependencia, sino una herramienta para **tus** cosas.
6. **Fresco:** sin pesadez, malos diseños o funcionalidad sin estética. Switer busca ser una app bonita y con lo que necesitas.
7. **Personal:** Switer es tuyo, y no solo por la licencia MIT. Busca la mejor experiencia para cada usuario, porque el **PKM** es **P**ersonal.
8. **Robusto:** con menos errores, mayor resiliencia y soluciones óptimas.

## Desarrollo
Switer está siendo desarrollado en Svelte-SvelteKit y será empaquetado como app en Tauri cuando esté listo. Para contribuir al código, es recomendable conocer estas herramientas y sus dependencias.

### Instalación

#### Requisitos
Antes de comenzar, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (v18 o superior)
- [pnpm](https://pnpm.io/) (gestor de paquetes, opcional pero recomendado)
- [Rust](https://www.rust-lang.org/) (requerido por Tauri)
- Un compilador C/C++:
    - En Windows: [Microsoft Visual Studio Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
    - En Linux: `build-essential`
    - En macOS: Xcode Command Line Tools (`xcode-select --install`)

#### Instrucciones
1. Clona la repo:

```Bash
git clone https://github.com/Andresit1524/Switer
cd Switer
```

2. Instala dependencias y ejecuta:

```Bash
pnpm install
pnpm dev
```

### Estado del proyecto (*10 de agosto de 2025*)
Actualmente Switer esta en fase de **prototipo**, de forma que no hay cambios o implementaciones importantes acá en el repositorio.

> ### Sobre su creador
> Soy Hayran Andrés López, un estudiante de ingeniería que busca desarrollar Switer como una forma de aprender sobre desarrollo web y de aplicaciones, y también para cumplir un objetivo: **crear lo mas cercano al PKM definitivo**, ofreciendo una experiencia completa y un software libre y de calidad.
> 
> Me encanta Obsidian, y quiero que sus bondades estén en manos de todos, no robando el software, sino ofreciendo uno que potencie sus fortalezas, corrija sus deficiencias y ofrezca una versión única de un PKM, el tipo de software que todos merecen disfrutar.
>
> Puedes preguntarme sobre el proyecto y contribuir a él (con ideas o en el repo) [en este correo](mailto:hayranlopez1524@gmail.com)
