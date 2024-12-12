# Adalab-proyecto-da-promo-xyz-modulo-1-team-3
## Primer proyecto. Módulo1. Juegos clásicos.
Las componentes del equipo, y por tanto autoras de estos juegos son:
- Carlota Gómez Martínez.
- Katherine Gortz Rogers.
- Tahiera Jafari.
- Lucía Nozal Benito.

Los juegos que se van a ver en este proyecto son:
- Piedra, papel o tijera.
- Ahorcado.
- Preguntas y respuestas teniedno con temática la geografía.
- Tic tac toe.
### Juego 1 - PIEDRA, PAPEL O TIJERA 🪨📃✂️

¡Bienvenido al juego clásico de Piedra, Papel o Tijera! En este juego podrás enfrentarte contra el contrincante virtual. El primero en ganar 3 rondas será el vencedor. ¡Vamos a divertirnos!

Las reglas del juego son:
- Piedra 🪨 vence a Tijera ✂️
- Tijera ✂️ vence a Papel 📃
- Papel 📃 vence a Piedra 🪨
- Si ambos eligen lo mismo, es un empate.
- El jugador que gana una ronda obtiene un punto.
- El juego continúa hasta que un jugador haya acumulado 3 puntos, convirtiéndose en el ganador.

#### ⚡Como jugar:

1. El juego comienza pidiéndote que introduzcas tu nombre. Si no lo haces, se te asignará el nombre predeterminado "Jugador Anónimo".

2. En cada ronda, deberás elegir entre tres opciones:

  - Piedra 🪨
  - Papel 📃
  - Tijera ✂️

  - OJO: El programa verifica que la palabra indicada por el jugador sea una de las tres opciones válidas:
```
  elementos_validos = ["PIEDRA", "PAPEL", "TIJERA"]
  ```

  En caso contrario, se ejecutará el siguiente código:
```
if seleccion_humano not in elementos_validos:

        print("⚠ El elemento introducido no está entre la selección permitida.⚠ Te recuerdo los elementos permitidos: piedra 🪨, papel 📃 o tijera✂️.")
```


3. Tu contrincante virtual elegirá aleatoriamente entre las mismas tres opciones.

4. El programa se compararán las jugadas según las reglas del juego:
         Piedra gana a Tijera
         Tijera gana a Papel
         Papel gana a Piedra
         Si ambos eligen igual, es un empate

5. El ganador de la ronda obtiene un punto. El juego continuará hasta que uno de los jugadores gane 3 rondas. 

#### Ejemplo del juego
```
¡BIENVENIDO@ AL JUEGO DE PIEDRA 🪨, PAPEL 📃 O TIJERA ✂️! Indícanos cómo te llamas

¿Cómo te llamas? Maria

¡¡Hola 👏🏻 Maria!! Yo soy Pepe, tu contrincante virtual 🖥️, y voy a intentar ganarte siempre 😜,
¡espero que lo pasemos genial! El primero en ganar 3 rondas será el ganador del juego, ¡suerte! 🍀

---------- RONDA 1 ----------
Elementos elegidos:
Maria - PIEDRA
Pepe - TIJERA

¡¡¡Muy bien Maria!!! 😎 Me has ganado esta ronda amig@ humano.
Maria - 1 || Pepe - 0

---------- RONDA 2 ----------
Elementos elegidos:
Maria - PAPEL
Pepe - PIEDRA

¡¡¡Muy bien Maria!!! 😎 Me has ganado esta ronda amig@ humano.
Maria - 2 || Pepe - 0

...

🎉¡¡¡Felicidades Maria!!!🎉 Me has ganado con una puntuación de 3 a 1 😉.
```

#### Tecnologías
   - Lenguaje usado: Python
   - Módulo estándar random (incluido en Python).
   - Entorno usado: Visual Studio Code
   - Github Repositories
   - Git Project
   - Consultas a fuentes en internet 

#### Características
  - Funcionalidad para personalizar el nombre del jugador
  - Verificación de entradas inválidas
  - Mensajes interactivos y uso de emoticonos para crear una experiencia divertida
  - Sistema dinámica de acumulación de puntos

  #### Posibles mejoras
  - Implementar una modilidad multi-jugador
  - Agregar una opción para jugar múltiples partidos. 

### Reglas del juego 2 - AHORCADO
- Un jugador elige una palabra secreta y dibuja un espacio para cada letra de la palabra.
- El otro jugador intenta adivinar letras para completar la palabra.
- Si el jugador adivinador adivina una letra correctamente, se revela en su lugar correspondiente.
- Si el jugador adivinador adivina incorrectamente, se dibuja una parte del cuerpo en la horca.
- El objetivo del jugador adivinador es adivinar la palabra antes de que se dibuje el dibujo completo en la horca.
### Reglas del juego 3 - PREGUNTAS Y RESPUESTAS
- El juego consiste en hacer preguntas de geografía y que el jugador adivine la respuesta correcta.
- Cada pregunta tiene una respuesta única y correcta.
- El jugador tiene un número limitado de intentos para responder correctamente a cada pregunta.
- El juego sigue hasta que el jugador responda incorrectamente 3 de veces o haya respondido 5 preguntas correctamente.
### Reglas del juego 4 - TIC, TAC, TOE
- El juego se juega en un tablero de 3x3.
- Dos jugadores, uno representa "X" y el otro "O", alternan turnos.
- El objetivo es obtener tres símbolos del mismo tipo en línea horizontal, vertical o diagonal.
- El juego termina cuando un jugador gana o el tablero se llena (empate).
- El jugador que logre colocar tres de sus símbolos en línea es el ganador.
tecnologías usadas, como jugar, mejoras, como está hecho