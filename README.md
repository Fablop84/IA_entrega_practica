# 🤘 Metalpedia

<img width="1540" height="808" alt="image" src="https://github.com/user-attachments/assets/6237ec40-91d7-4e74-8cc1-4ac50c914dbd" />

![Status](https://img.shields.io)
![Built with Lovable](https://img.shields.io)

> [!TIP]
> **🚀 Prueba la App aquí:** [https://metal-lore-hub.lovable.app](https://metal-lore-hub.lovable.app)

**Metalpedia** es una enciclopedia interactiva para fans del metal...


**Metalpedia** es una enciclopedia interactiva para fans del metal. Permite consultar fichas técnicas de bandas, explorar álbumes, verificar tours vigentes y conectar con una comunidad activa a través de reseñas y perfiles sociales.

> [!IMPORTANT]
> Este MVP ha sido generado y prototipado utilizando **Lovable**, basándose en las especificaciones definidas en nuestro documento de requisitos.

## 🚀 Funcionalidades del MVP

- **Exploración Total:** Fichas de bandas con biografía, fotos y discografía.
- **Conectividad Social:** Sistema de reviews, calificaciones y perfiles de usuario con lista de amigos.
- **Tours en Vivo:** Consulta de fechas y giras actuales.
- **Motor de Recomendación:** Sugerencias inteligentes de bandas similares para fomentar el descubrimiento.
- **Acceso Simple:** Login mediante correo electrónico para personalización de la experiencia.

## 🤖 Desarrollo con IA
Este repositorio es el resultado de una práctica de IA donde se utilizó un prompt estructurado para definir un **PRD** (Product Requirements Document), el cual fue posteriormente procesado por **Lovable** para generar la aplicación funcional.

## 📦 Documentación
- **PRD.md(./PRD.md):** Documento detallado con el alcance, requisitos funcionales y métricas de éxito.

- PRD.md
Contexto y objetivo
Crear una enciclopedia digital de bandas de metal para fans (casuales y expertos) que centralice información sobre géneros, álbumes y tours, fomentando el descubrimiento de música y la interacción entre usuarios a través de reseñas y redes sociales internas.
Usuario objetivo
Fans casuales que buscan descubrir nuevos sonidos y leer opiniones.
Expertos en metal que desean registrar sus reseñas y conectar con otros fans.
Caso de uso principal
El usuario busca una banda, consulta su ficha técnica, deja una reseña sobre un álbum y visita el perfil de otro usuario para ver sus bandas recomendadas.
Alcance
In scope
Buscador de bandas por nombre y género.
Ficha técnica: Fotos, reseñas editoriales, discografía y tours vigentes.
Sistema de reviews: Espacio para que los usuarios dejen comentarios y calificaciones.
Perfiles sociales: Perfil de usuario con lista de amigos y actividad reciente.
Recomendaciones de bandas similares.
Login simplificado mediante correo electrónico.
Diseño responsivo (Web y Móvil).
Out of scope
Venta directa de tickets de conciertos.
Reproductor de música integrado (streaming completo).
Chats privados entre usuarios (se mantiene en comentarios públicos).
Requisitos funcionales
FR-01: El sistema debe permitir la búsqueda de bandas por texto libre.
FR-02: El sistema debe mostrar una ficha de banda con biografía, discografía y tours.
FR-03: El usuario podrá publicar reseñas de texto y puntuaciones en las fichas de las bandas.
FR-04: El sistema debe permitir agregar a otros usuarios como "amigos" para ver su actividad.
FR-05: El sistema debe permitir el acceso del usuario mediante ingreso de email.
FR-06: El sistema debe sugerir bandas basadas en el género consultado.
Requisitos no funcionales
Compatibilidad: Interfaz 100% responsiva.
Rendimiento: Carga eficiente de feeds de comentarios y listas de amigos.
Moderación: Filtros básicos de palabras prohibidas para las reseñas.
Métrica de éxito
Tiempo de permanencia en la página.
Número de reseñas publicadas por usuario.
Cantidad de solicitudes de amistad enviadas/aceptadas.
Dependencias y riesgos
Dependencias: APIs externas de música (ej. Spotify, MusicBrainz) para datos técnicos.
Riesgos: Necesidad de moderación de contenido en reseñas para evitar spam o toxicidad.
Open questions / Suposiciones
Suposición: El perfil social mostrará públicamente las bandas favoritas y las reseñas escritas por el usuario.
Suposición: Al no haber contraseña, el perfil se vincula permanentemente al email ingresado.
Pregunta: ¿Las reseñas deben ser aprobadas por un administrador antes de publicarse o son instantáneas?

## 🛠️ Tecnologías
- **Core:** React / Vite (generado vía Lovable).
- **Styling:** Tailwind CSS.
- **Backend/Auth:** Supabase (configuración por defecto de Lovable).

## Link del página

https://metal-lore-hub.lovable.app 

---
*Creado para la práctica de IA - 2026*
*
