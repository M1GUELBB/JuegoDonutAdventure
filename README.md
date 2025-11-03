En este repositorio tenemos acceso al ejecutable de un pequeño juego realizado por mi, a modo de investigacion en el desarrollo de los videojuegos, creado en Unity (con lenguaje c++).


Donut Adventure
"Donut Adventure" es un juego de plataformas arcade en 2D que combina acción trepidante, rejugabilidad y desafíos progresivos. Está diseñado para ser accesible para todos los públicos pero a la vez competitivo , motivando a los jugadores a superar sus propias puntuaciones.



🕹️ Gameplay

El objetivo principal es sobrevivir el mayor tiempo posible mientras se recolectan donuts y se superan obstáculos.
Movimiento: El personaje avanza automáticamente hacia adelante , escapando de una serpiente que lo persigue. Si la serpiente toca al jugador, el juego termina.



Controles (PC):

Salto simple: Barra espaciadora 
Salto doble: Doble Barra espaciadora. Este salto es 1.5 veces más alto que el salto normal y se usa para superar obstáculos de mayor tamaño
Pausa: Tecla P 
Puntuación y Progresión: Los jugadores ganan puntos recolectando donuts. A medida que el juego avanza, la velocidad del personaje y la frecuencia de aparición de obstáculos aumentan progresivamente
Obstáculos y Vidas: El jugador debe evitar varios enemigos. Al colisionar con un obstáculo (como un murciélago, piedras o cajas), el jugador pierde una vida. El juego termina cuando se agotan todas las vidas.



✨ Características

Personaje Principal: Un personaje de estilo pixel art llamado "comilón" (nombre por defecto) , con animaciones para correr, saltar y caer.
Enemigos y Obstáculos:
- Serpiente: Persigue al jugador desde atrás.
- Murciélago: Enemigo volador que resta una vida al chocar.
- Piedras y Cajas: Obstáculos en el suelo que también restan una vida.



HUD (Interfaz Gráfica): La interfaz muestra las vidas actuales del jugador (en la esquina superior izquierda, como corazones ) y la puntuación (en la esquina superior derecha ).



🛠️ Implementación Técnica
Este proyecto se desarrolló como una versión beta utilizando el motor de videojuegos Unity. La programación se realizó en C++, centrándose en el trabajo con objetos y la relación entre las distintas clases.



Desafíos del Desarrollo
Durante la creación del juego, se encontraron varias dificultades principales:
- Colisiones: Controlar correctamente las colisiones del personaje con los distintos obstáculos y recompensas.
- Animaciones: La implementación de las animaciones del jugador.
- Programación: El trabajo con objetos y la gestión de relaciones entre clases en C++.
- Interfaz (HUD): Asegurar la correcta actualización de las vidas y la puntuación en la vista del juego.

  

🚀 Mejoras Futuras
Dado que esta es una versión inicial , hay varias características planeadas para futuras actualizaciones:
- Un menú inicial con selección de distintos personajes.
- Tablas de puntuación al final de la partida.
- Inclusión de potenciadores para cambiar la dinámica del juego, como "velocidadx2", "supersalto" o un escudo de inmunidad temporal.


Miguel Buitrago Blanco
