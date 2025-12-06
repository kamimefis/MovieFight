# Movie Fight – Comparador de Películas

## Aplicación web interactiva que compara dos películas lado a lado usando la API pública de OMDb.
El usuario escribe el título, selecciona la película correcta desde un autocompletado y la app muestra una comparación visual con datos clave.

### Características principales
- Búsqueda predictiva con autocompletado
- Comparación de dos películas (Movie vs. Movie)
- Indicadores de comparación:
- Rating de IMDb
- Votos totales
- Metascore
- Premios
- Recaudación en taquilla
- Sistema de “ganador” dinámico
- Interfaz limpia y responsiva
- Modo oscuro
- Consumo de API en tiempo real usando Axios
- Basado en HTML + JavaScript vanilla + Bulma CSS

### Estructura del proyecto
movie-fight\
├── index.html\
├── styles.css\
├── script.js\
├── utils.js\
├── autocomplete.js\
└── README.md\

### Requisitos
Este proyecto no requiere backend ni entorno Node.
Solo necesitas:

- Un navegador moderno
- Conexión a internet para consultar la API de OMDb
- Una API Key válida de OMDb (gratuita

### Cómo usar la app
- Escribe el nombre de una película en cada buscador.
- Selecciona una opción del menú desplegable.
- Se cargará automáticamente toda la información.
- Compara visualmente los indicadores.
- Cada categoría se resalta según cuál película tiene el mejor valor.

### Tecnologías usadas
- HTML5
- JavaScript (ES6)
- Bulma CSS (Dark Mode personalizado)
- Axios
- OMDb API
