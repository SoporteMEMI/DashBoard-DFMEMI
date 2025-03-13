# DashBoard DFMEMI

Este proyecto es un tablero de control que utiliza iframes para mostrar diferentes páginas de Power BI. A continuación se describen las funcionalidades principales y cómo utilizarlas.

## Funcionalidades

### Rotación de iframes

El tablero permite la rotación automática de iframes, mostrando cada página durante un tiempo determinado.

- **Iniciar rotación**: Presiona el botón "Iniciar" para comenzar la rotación automática de las páginas.
- **Detener rotación**: Presiona el botón "Detener" para detener la rotación automática.

### Navegación manual

Puedes navegar manualmente entre las páginas utilizando los botones de navegación.

- **Anterior**: Presiona el botón "←" para ir a la página anterior.
- **Siguiente**: Presiona el botón "→" para ir a la página siguiente.
- **Navegación directa**: Utiliza los botones de navegación para ir directamente a una página específica.

### Refresco de páginas

El tablero permite refrescar todas las páginas manualmente o en horarios programados.

- **Refrescar manualmente**: Presiona el botón "Refrescar" para recargar todas las páginas.
- **Refrescos automáticos**: Las páginas se refrescan automáticamente en los siguientes horarios:
  - 05:40
  - 08:10
  - 09:10
  - 10:40
  - 12:40
  - 13:40
  - 14:40
  - 15:40

## Cómo usar

1. Abre el archivo `index.html` en tu navegador.
2. Utiliza los controles en la esquina superior derecha para navegar, iniciar/detener la rotación y refrescar las páginas.

## Personalización

Puedes personalizar las URLs de los iframes y la duración de cada página modificando las siguientes variables en el script:

```javascript
const iframes = [
    "URL_DE_TU_IFRAME_1",
    "URL_DE_TU_IFRAME_2",
    // ...otras URLs
];

let pageDuration = 25000; // Duración de cada página en milisegundos
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que te gustaría realizar.

## Licencia

Este proyecto no tiene una licencia definida aún.
