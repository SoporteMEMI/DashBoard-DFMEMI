# DashBoard DFMEMI

Este proyecto es un tablero de control interactivo para DFMEMI, que utiliza iframes para mostrar diferentes páginas de Power BI. El tablero permite la rotación automática entre las páginas, así como la navegación manual.

## Estructura del Proyecto

- `index.html`: El archivo principal que contiene la estructura HTML, estilos CSS y scripts JavaScript para el tablero.

## Configuración

1. Clona el repositorio en tu máquina local:
    ```sh
    git clone https://github.com/SoporteMEMI/DashBoard-DFMEMI.git
    ```

2. Navega al directorio del proyecto:
    ```sh
    cd DashBoard-DFMEMI
    ```

3. Abre el archivo `index.html` en tu navegador preferido.

## Uso

- **Iniciar Rotación**: Haz clic en el botón "Iniciar" para comenzar la rotación automática entre las páginas.
- **Detener Rotación**: Haz clic en el botón "Detener" para detener la rotación automática.
- **Refrescar Páginas**: Haz clic en el botón "Refrescar" para recargar todas las páginas.
- **Navegación Manual**: Usa los botones de navegación (←, →) para moverte entre las páginas manualmente.
- **Ir a Página Específica**: Haz clic en los botones de navegación específicos para ir a una página en particular.

## Personalización

Puedes personalizar las URLs de los iframes modificando el arreglo `iframes` en el archivo `index.html`:
```javascript
const iframes = [
    "URL_DE_TU_IFRAME_1",
    "URL_DE_TU_IFRAME_2",
    // ...otras URLs
];
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que te gustaría hacer.

## Licencia

Este proyecto no tiene una licencia definida aún.
