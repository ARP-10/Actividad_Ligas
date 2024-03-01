# Ligas - Gestión Deportiva ⚽🏆

## Descripción
Este proyecto se enfoca en la creación de una aplicación para gestionar eficazmente ligas deportivas. La aplicación proporciona herramientas para administrar ligas, equipos y partidos, con el objetivo de simplificar y mejorar la organización de competiciones deportivas.

## Base de Datos 📊
La aplicación utiliza una base de datos con la siguiente estructura:
- **Ligas:** id_liga, nombre_liga, fecha_inicio, fecha_fin
- **Equipos:** id_equipo, nombre_equipo, ciudad, id_liga
- **Partido:** id_partido, fecha_partido, goles_equipo_local, goles_equipo_visitante, id_equipo_local, id_equipo_visitante, id_liga

## Tecnologías Utilizadas 💻
- Java
- Hibernate (ORM)
- Swing o JavaFX (Interfaz Gráfica, opcional)
