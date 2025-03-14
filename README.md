# DashBoard DFMEMI

Este proyecto es un dashboard interactivo que muestra varias páginas de informes de Power BI. Las páginas se rotan automáticamente y se pueden controlar manualmente mediante botones de navegación.

## Características

- Rotación automática de páginas.
- Control manual para iniciar, detener, avanzar y retroceder entre las páginas.
- Refresco automático de todas las páginas en horarios específicos.
- Botones de navegación para acceder directamente a una página específica.

## Uso

Al cargar la página, la rotación de las páginas se inicia automáticamente y el botón "Iniciar" se activa por defecto.

### Programación de Refrescos Automáticos

Las páginas se refrescan automáticamente en los siguientes horarios:

- 05:40
- 08:10
- 09:10
- 10:40
- 12:40
- 13:40
- 14:40
- 15:40

### Controles

- **Iniciar**: Inicia la rotación automática de las páginas.
- **Detener**: Detiene la rotación automática de las páginas.
- **Refrescar**: Refresca manualmente todas las páginas.
- **←**: Va a la página anterior.
- **→**: Va a la página siguiente.
- **Índice, Nuestra Gente, DFMEMI en Números, Solicitudes del Personal, Solicitudes a DFMEMI, Fiscalizaciones, DFMEMI**: Navega directamente a la página seleccionada.

## Instalación

1. Clona el repositorio.
2. Abre el archivo `index.html` en tu navegador.

## Personalización

Para cambiar las URLs de los iframes, modifica el array `iframes` en el archivo `index.html`:

```javascript
const iframes = [
    "URL1",
    "URL2",
    "URL3",
    // ...
];
```

Para ajustar la duración de cada página, modifica la variable `pageDuration` en milisegundos:

```javascript
let pageDuration = 25000; // 25 segundos
```

Para cambiar los horarios de refresco automático, ajusta las llamadas a `scheduleRefresh` en el evento `window.onload`:

```javascript
window.onload = () => {
    // ...existing code...
    scheduleRefresh(5, 40);
    scheduleRefresh(8, 10);
    // ...existing code...
};
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que te gustaría realizar.

## Licencia

Este proyecto no tiene una licencia definida aún.
