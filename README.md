
# Movies Web

Este proyecto es una aplicación web para el consumo de una API de películas. Permite a los usuarios explorar tendencias, buscar películas, ver detalles de cada una y navegar entre categorías de una manera visual y atractiva.

## Características

- **Explorar tendencias:** Visualiza las películas más populares del momento.
- **Búsqueda:** Busca películas por título.
- **Categorías:** Navega por diferentes géneros de películas.
- **Detalles:** Obtén información detallada de cada película.
- **Diseño responsivo:** Adaptado para dispositivos móviles y de escritorio.
- **Interactividad:** Navegación mejorada con flechas para el desplazamiento.

## Tecnologías utilizadas

- **Frontend:**
  - HTML5
  - CSS3 (con diseño elegante y animaciones)
  - JavaScript (para manejar la lógica de la interacción)
- **API:**
  - Consumo de una API REST para obtener datos dinámicos de películas.

## Estructura del proyecto

```plaintext
movies-web/
├── index.html        # Archivo principal de la aplicación
├── styles/
│   ├── app.css       # Estilos personalizados
├── src/
│   ├── main.js       # Lógica principal de la aplicación
│   ├── api.js        # Configuración y consumo de la API
│   ├── navigation.js # Manejo de rutas y navegación
├── assets/
│   ├── images/       # Imágenes utilizadas en el proyecto
└── README.md         # Documentación del proyecto
```

## Configuración

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/movies-web.git
   cd movies-web
   ```

2. **Instalar dependencias (si es necesario):**
   ```bash
   npm install
   ```

3. **Configurar la API:**
   - Crear un archivo `src/secrets.js` con tu clave de API:
     ```javascript
     export const API_KEY = 'TU_API_KEY_AQUI';
     ```

4. **Ejecutar la aplicación:**
   - Abre el archivo `index.html` en tu navegador o utiliza una extensión de servidor local como **Live Server**.

## Funcionalidades futuras

- Agregar autenticación de usuarios para listas personalizadas.
- Funcionalidad para marcar películas como favoritas.
- Agregar un reproductor de trailers.
- Mejorar la paginación y carga de contenido infinito.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---
