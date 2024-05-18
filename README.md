# Snake Game

## Description
Welcome to the Snake Game! This classic arcade game is developed using Python and the Turtle graphics module. Guide the snake to eat food, grow longer, and try to achieve the highest score possible without colliding with the walls or the snake's own body.

## Prerequisites
Ensure you have Python installed on your system. You can download Python from the [official website](https://www.python.org/).

You will also need to install the `turtle` module if it's not already installed. You can do this using pip:
```bash
pip install PythonTurtle
```

## Instructions to Play
1. **Clone or Download the Repository**: Obtain the game files by cloning this repository or downloading the ZIP file and extracting it.

2. **Navigate to the Game Directory**: Open a terminal (or command prompt) and navigate to the directory where the game files are located.
   ```bash
   cd path/to/game/directory
   ```

3. **Run the Game**: Execute the `main.py` file to start the game.
   ```bash
   python main.py
   ```

4. **Game Controls**: Use the arrow keys on your keyboard to control the snake's movement:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right

5. **Gameplay**:
   - The snake will start moving in the direction it is facing.
   - Guide the snake to eat the blue food that appears randomly on the screen.
   - Each time the snake eats food, it will grow longer, and your score will increase.
   - Avoid colliding with the walls or the snake's own body, as this will reset your score and the snake.

6. **High Score**:
   - The game tracks your high score, which is saved in a file named `data.txt`.
   - If you achieve a new high score, it will be updated in the `data.txt` file.

## Files Overview
- `main.py`: The main file to run the game.
- `snake.py`: Contains the Snake class, managing the snake's movement and growth.
- `food.py`: Contains the Food class, managing the appearance and placement of the food.
- `scoreboard.py`: Contains the Scoreboard class, managing the score display and high score tracking.
- `data.txt`: A text file to store the high score.

## Troubleshooting
- If the game doesn't start, ensure that all the required files (`main.py`, `snake.py`, `food.py`, `scoreboard.py`, `data.txt`) are in the same directory.
- Ensure you have the necessary permissions to read and write to the `data.txt` file.
- Make sure you are using a compatible version of Python (preferably 3.x).

Enjoy playing the Snake Game! Try to beat your high score and have fun!

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# Juego de la Serpiente

## Descripción
¡Bienvenido al Juego de la Serpiente! Este clásico juego de arcade está desarrollado utilizando Python y el módulo gráfico Turtle. Guía a la serpiente para que coma comida, crezca y trata de lograr la mayor puntuación posible sin chocar con las paredes o con el propio cuerpo de la serpiente.

## Requisitos Previos
Asegúrate de tener Python instalado en tu sistema. Puedes descargar Python desde el [sitio web oficial](https://www.python.org/).

También necesitarás instalar el módulo `turtle` si no está ya instalado. Puedes hacerlo usando pip:
```bash
pip install PythonTurtle
```

## Instrucciones para Jugar
1. **Clona o Descarga el Repositorio**: Obtén los archivos del juego clonando este repositorio o descargando el archivo ZIP y extrayéndolo.

2. **Navega al Directorio del Juego**: Abre una terminal (o símbolo del sistema) y navega al directorio donde se encuentran los archivos del juego.
   ```bash
   cd ruta/al/directorio/del/juego
   ```

3. **Ejecuta el Juego**: Ejecuta el archivo `main.py` para iniciar el juego.
   ```bash
   python main.py
   ```

4. **Controles del Juego**: Usa las teclas de flechas en tu teclado para controlar el movimiento de la serpiente:
   - **Flecha Arriba**: Mover hacia arriba
   - **Flecha Abajo**: Mover hacia abajo
   - **Flecha Izquierda**: Mover hacia la izquierda
   - **Flecha Derecha**: Mover hacia la derecha

5. **Jugabilidad**:
   - La serpiente comenzará a moverse en la dirección en la que esté orientada.
   - Guía a la serpiente para que coma la comida azul que aparece aleatoriamente en la pantalla.
   - Cada vez que la serpiente coma comida, se hará más larga y tu puntuación aumentará.
   - Evita chocar con las paredes o con el propio cuerpo de la serpiente, ya que esto reiniciará tu puntuación y la serpiente.

6. **Puntuación Más Alta**:
   - El juego rastrea tu puntuación más alta, que se guarda en un archivo llamado `data.txt`.
   - Si logras una nueva puntuación más alta, se actualizará en el archivo `data.txt`.

## Resumen de Archivos
- `main.py`: El archivo principal para ejecutar el juego.
- `snake.py`: Contiene la clase Snake, que gestiona el movimiento y crecimiento de la serpiente.
- `food.py`: Contiene la clase Food, que gestiona la aparición y colocación de la comida.
- `scoreboard.py`: Contiene la clase Scoreboard, que gestiona la visualización de la puntuación y el seguimiento de la puntuación más alta.
- `data.txt`: Un archivo de texto para almacenar la puntuación más alta.

## Solución de Problemas
- Si el juego no se inicia, asegúrate de que todos los archivos necesarios (`main.py`, `snake.py`, `food.py`, `scoreboard.py`, `data.txt`) estén en el mismo directorio.
- Asegúrate de tener los permisos necesarios para leer y escribir en el archivo `data.txt`.
- Asegúrate de estar usando una versión compatible de Python.

¡Disfruta jugando al Juego de la Serpiente! Trata de superar tu puntuación más alta y diviértete.
