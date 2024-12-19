# Adalab-proyecto-da-promo-l47-modulo-1-team-3
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

### Juego 1 - PIEDRA, PAPEL O TIJERA 🪨📃✂️

¡Bienvenid@ al juego clásico de Piedra, Papel o Tijera! En este juego podrás enfrentarte contra el contrincante virtual. El primero en ganar 3 rondas será el vencedor. ¡Vamos a divertirnos!

Las reglas del juego son:
- Piedra 🪨 vence a Tijera ✂️.
- Tijera ✂️ vence a Papel 📃.
- Papel 📃 vence a Piedra 🪨.
- Si ambos eligen lo mismo, es un empate.
- El jugador que gana una ronda obtiene un punto.
- El juego continúa hasta que un jugador haya acumulado 3 puntos, convirtiéndose en el ganador.

#### ⚡Como jugar:

1. El juego comienza pidiéndote que introduzcas tu nombre. Si no lo haces, se te asignará el nombre predeterminado "Jugador Anónimo".

2. En cada ronda, deberás elegir entre tres opciones:

  - Piedra 🪨.
  - Papel 📃.
  - Tijera ✂️.

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
         Piedra gana a Tijera.
         Tijera gana a Papel.
         Papel gana a Piedra.
         Si ambos eligen igual, es un empate.

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
   - Lenguaje usado: Python.
   - Módulo estándar random (incluido en Python).
   - Entorno usado: Visual Studio Code.
   - Github Repositories.
   - Git Project.
   - Consultas a fuentes en internet.

#### Características
  - Funcionalidad para personalizar el nombre del jugador.
  - Verificación de entradas inválidas.
  - Mensajes interactivos y uso de emoticonos para crear una experiencia divertida.
  - Sistema dinámica de acumulación de puntos.

  #### Posibles mejoras
  - Implementar una modilidad multi-jugador.
  - Agregar una opción para jugar múltiples partidos. 

### Juego 2 - AHORCADO 🔤📝

¡Bienvenid@ al juego clásico del Ahorcado! Pon a prueba tu ingenio mientras intentas adivinar la palabra secreta antes de que se agoten tus intentos para adivinar las letras de esa palabra. Dispones de hasta 6 oportunidades para equivocarte.

Con cada error, se dibuja una parte del cuerpo del pobre muñequito en la horca. Si logras completar la palabra a tiempo, ¡serás el héroe que lo salva! Pero si no lo consigues... bueno, ya sabes: ☠️🪓

Ten estas reglas en cuenta:

- Solo puedes ingresar una letra a la vez.
- Letras repetidas no afectarán tus intentos, pero recibirás un aviso.

#### ⚡Como jugar:

1. El juego comienza pidiéndote que introduzcas tu nombre. Si no lo haces, se te asignará el nombre predeterminado "Jugador Anónimo".

2. Recibirás una palabra secreta que deberás adivinar, la cual estará representada con guiones bajos: _ _ _ _.

3. Adivina una letra escribiéndola y presionando "Enter" en tu teclado. Si la letra está en la palabra, se revelará en su posición correspondiente.
Si no está, se suma un intento fallido. 

- ⚠️Puedes fallar hasta 6 veces. Después, pierdes y el juego terminará.

- 🎉Si completas la palabra antes de quedarte sin intentos, ¡ganas!

#### Tecnologías
   - Lenguaje usado: Python.
   - Módulo estándar random (incluido en Python).
   - Entorno usado: Visual Studio Code.
   - Github Repositories.
   - Git Project.
   - Consultas a fuentes en internet.
   - Dibujos preprados para las fases del desarrollo del muñequito en la horca (Fuente: ChatGPT).

#### Características
  - Funcionalidad para personalizar el nombre del jugador.
  - Mensajes interactivos y uso de emoticonos para crear una experiencia divertida.
  - Verificación de entradas inválidas: Si el jugador introduce un número, símbolo o más de una letra (la primera línea del código a continuación), se ejecutará este código:

  ```
  letra = input("Adivina una letra: ").strip().lower()
  
  if len(letra) != 1 or not letra.isalpha():
        print("\n\nUps, ¡solo se puede introducir una letra!, inténtalo de nuevo 🔃.")
```

  #### Posibles mejoras
  - Agregar una opción para jugar múltiples partidos. 
  - Implemenar el uso de PyDictionary para generar la palabra secreta en lugar de difinir la lista en el programa. 



### Juego 3 - Juego de Preguntas y Respuestas sobre Geografía 🌍

¡Bienvenid@ al Juego de Preguntas y Respuestas sobre Geografía! Pon a prueba tus conocimientos sobre geografía. Tu objetivo es contestar correctamente 5 preguntas con un un máximo de 3 respuestas incorrectas, ¡así que ten cuidado con lo que contestas! 😅

Las reglas del juego son:
- Cada pregunta tiene una respuesta única y correcta.
- El juego sigue hasta que el jugador responda incorrectamente 3 de veces o haya respondido 5 preguntas correctamente.
- No te preocupes por las tildes ni por las mayúsculas y minúsculas, contaremos tu respuesta como correcta independientemente de estos factores. ¡Pero debes cuidar la ortografía!📚✍️

#### ⚡Como jugar:

1. El juego comienza pidiéndote que introduzcas tu nombre. Si no lo haces, se te asignará el nombre predeterminado "Jugador Anónimo".

2. Responde las preguntas: Cada ronda incluye una pregunta de geografía. El jugador debe ingresar su respuesta y el juego verificará si es correcta.

3. Se implementa el siguiente sistema de puntuación:
El jugador puede acertar hasta 5 preguntas.
El jugador puede equivocarse hasta 3 veces.

4. Finalización del juego: El juego termina cuando se alcanzan 5 respuestas correctas o 3 respuestas incorrectas.
Si el jugador obtiene 5 respuestas correctas, ¡felicidades! 🎉
Si el jugador alcanza 3 respuestas incorrectas, el juego termina y muestra un mensaje animando al jugador a volver a probar su suerte repitiendo el juego. 

### Preguntas de ejemplo:
¿Dónde se encuentra el Monte Fuji?
Respuesta correcta: Japón. (También se admite la respuesta: Japon.)

¿Cuál es el río más grande de España?
Respuesta correcta: Ebro.

¿En qué país se encuentra la Torre Eiffel?
Respuesta correcta: Francia.

#### Tecnologías
   - Lenguaje usado: Python.
   - Módulo estándar random (incluido en Python).
   - Módulo estándar unicodedata (incluido en Python).
   - Entorno usado: Visual Studio Code.
   - Github Repositories.
   - Git Project.
   - Consultas a fuentes en internet.
 
#### Características
  - Funcionalidad para personalizar el nombre del jugador.
  - Mensajes interactivos y uso de emoticonos para crear una experiencia divertida.GIT
  - Las preguntas son seleccionadas al azar de un conjunto de preguntas preparadas, y no se repiten hasta que todas hayan sido respondidas.
  - Uso de la función normalize del módulo unicodedata para "normalizar" la respuesta de cada pregunta cadena de texto para facilitar las comparaciones entre cadenas sin preocuparse por los tildes.

  ```
import unicodedata

# Función para eliminar tildes y normalizar texto
def normalizar_tildes(palabra):
    # Normaliza la palabra y elimina las marcas de acento
    palabra_normalizada = unicodedata.normalize('NFD', palabra)
    caracteres_sin_tildes = []

    for caracter in palabra_normalizada:
        if unicodedata.category(caracter) != 'Mn':  # Si no es un acento
            caracteres_sin_tildes.append(caracter)
    
    return ''.join(caracteres_sin_tildes)

# Función para comparar las respuestas del jugador con la respuesta correcta
def comparar_palabras(palabra1, palabra2):
    return normalizar_tildes(palabra1) == normalizar_tildes(palabra2)

# Ejemplo de uso con entrada del jugador
respuesta_correcta = "Japón"

# Simulando el input del jugador
respuesta_jugador = input("¿En qué país se encuentra el Monte Fuji? ")

# Mostrar la comparación de las respuestas
print(comparar_palabras(respuesta_jugador, respuesta_correcta))  # Salida esperada: True si el jugador responde "Japon" o "Japón"

```
  - Las minúsculas y mayúsculas no influyen si la respuesta es correcta o no. 


  #### Posibles mejoras
  - Agregar una opción para jugar múltiples partidos sin reiniciar el juego o de competir entre múltiples jugadores.
  - Ampliar el banco de preguntas. 
