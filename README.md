🎬 ScreenMatch - Catálogo de Series Inteligente
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
ScreenMatch es una aplicación robusta diseñada para la gestión y exploración de series televisivas. Integra el consumo de datos persistentes desde APIs externas, procesamiento inteligente con IA y una interfaz web moderna y dinámica. Este proyecto forma parte de la formación **Avanzando con Java** de Alura.
## 🖥️ Interfaz Web Dinámica
El proyecto cuenta con una **interfaz gráfica web completa** que permite visualizar el catálogo de series de manera profesional. Entre sus características principales destacan:
- **Detalle Exhaustivo:** Visualización de fichas técnicas completas (imagen de portada, sinopsis, evaluación).
- **Exploración por Temporadas:** Navegación fluida entre capítulos y temporadas de cada serie.
- **Sincronización en Tiempo Real:** Todos los datos (pósters, descripciones, puntuaciones) se obtienen dinámicamente desde la **OMDb API**.
- **Ranking Visual:** Sección de "Top 5" y "Lanzamientos Recientes" presentados con estética de plataforma de streaming.
## 🛠️ Tecnologías y Herramientas
### Backend (Core)
- **Java 17:** Versión estable para un desarrollo eficiente.
- **Spring Boot 3.2:** Framework base para la creación de la API REST.
- **Spring Data JPA:** Gestión simplificada de la capa de persistencia y consultas complejas a la base de datos.
- **PostgreSQL:** Base de datos relacional para el almacenamiento persistente de series y episodios.
- **Jackson:** Procesamiento de JSON para la comunicación con APIs y el cliente web.
### Integraciones y Servicios
- **OMDb API:** Fuente principal de metadatos cinematográficos.
- **IA (OpenAI / Google GenAI):** Implementación de traducción automática y enriquecimiento de descripciones para mejorar la experiencia del usuario.
## 🚀 Funcionalidades Destacadas
1. **Persistencia Inteligente:** Sistema que evita duplicidad de datos y sincroniza automáticamente episodios nuevos.
2. **Consultas Avanzadas:** 
- Filtrado por género (Categorías dinámicas).
- Búsqueda de episodios específicos por nombre utilizando consultas JPA personalizadas.
- Rankings dinámicos basados en la calificación de los usuarios.
3. **Traducción Automatizada:** Integración con modelos de lenguaje para ofrecer sinopsis siempre en el idioma preferido.
4. **Arquitectura API REST:** Desacoplamiento total entre el backend y la interfaz de usuario, facilitando la escalabilidad.
