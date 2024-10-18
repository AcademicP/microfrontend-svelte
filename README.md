
# vue-cw

Este proyecto es un **microfrontend Vue** desarrollado como parte del ecosistema **svelte-react-vue-angular-spa**. Su objetivo es proporcionar un sistema para la **gestión de importaciones tecnológicas** para la región de **Tingo María**. La aplicación está diseñada para integrarse de manera modular en Single-SPA, cargándose dinámicamente en un **modal flotante**.

---
Asegúrate de tener **Node.js** versión 16:

```bash
nvm install 16
```

## Configuración del Proyecto

### Instalación de dependencias

```bash
npm install
```

### Compilación y recarga en caliente para desarrollo

```bash
npm run serve
```

Accede a la aplicación en: [http://localhost:5004](http://localhost:5004)

### Compilación y minificación para producción

```bash
npm run build
```

### Linter y corrección de archivos

```bash
npm run lint
```

### Personalización de la Configuración

Consulta la [Documentación de Configuración](https://cli.vuejs.org/config/) para personalizar la configuración del proyecto.

---

## Integración con svelte-react-vue-angular-spa

Para ejecutar esta aplicación como parte del sistema **Single-SPA**, utiliza:

```bash
npm run serve
```

Esta aplicación se cargará dentro de un **modal flotante** cuando el usuario navegue a la ruta correspondiente en el root-config.

---

## Propósito del Proyecto

El objetivo principal de esta aplicación es **gestionar importaciones de productos tecnológicos** hacia **Tingo María**. Está diseñada para proporcionar un flujo ágil y eficiente de información, ayudando a los usuarios a gestionar datos de importación de manera centralizada.

### Características:
- Gestión de productos y proveedores tecnológicos.
- Integración modular como microfrontend en Single-SPA.
- Navegación sin recarga mediante modales flotantes.

---

## Scripts Disponibles

### `npm run serve`

Inicia el servidor de desarrollo.

### `npm run build`

Genera la versión de producción.

### `npm run lint`

Ejecuta el linter para detectar y corregir errores de estilo.

---

## Conclusión

Este **README.md** proporciona toda la información necesaria para desarrollar, ejecutar y mantener esta aplicación Vue como parte del ecosistema **svelte-react-vue-angular-spa**. Gracias a su integración modular, esta aplicación ofrece una **gestión eficiente y moderna** de importaciones tecnológicas para la región de **Tingo María**.
