# Pacman_AndresFuente
URL para poder jugar al juego completo: https://andresfuente.github.io/

Tareas Opcionales Implementadas:

-	Sprites con movimientos naturales: 

Los fantasmas tienen distintas animaciones dependiendo de la dirección en la que se mueven (Fijarse en los ojos de los fantasmitas).


-	Frutas:

Como podemos apreciar en el centro de la imagen, se generará cada cierto tiempo una fruta en esa posición del tablero. Si que es cierto que, al no implementar diferentes niveles, y con el fin de que no se muestre siempre la misma fruta, se ha declarado una variable “Random”, que decidirá que tipo de fruta aparece en cada partida. Como podemos observar abajo a la derecha de la imagen, se listarán las frutas disponibles según en número generado por el “Random” entre el 0 y el 8


-	Puntuación:  

En este caso si que he implementado toda la nueva funcionalidad. Como podemos observar en la parte inferior izquierda, se encuentran tres figuritas del comecocos, que representan las vidas restantes. Además en la parte superior podemos diferenciar dos bloques. Por una parte POINTS representa los puntos conseguidos en esa partida. HIGHSCORE en cambio representa la mejor puntuación obtenida en ese dispositivo, dado que se ayuda de la LocalStorage para guardar y recuperar la máxima puntuación obtenida.


-	Pausar el juego:
 
Por último también he implementado la funcionalidad de pausar y reanudar el juego. En vez de con la letra P, como sugería en el enunciado, he decidido utilizar la “Space Bar” o barra espaciadora, dado que me parece más práctico. Una vez pausado el juego, habrá que volver a pulsar sobre ella para reanudarlo. Se ha añadido el efecto de cuenta atrás a la hora de reanudar el juego.
