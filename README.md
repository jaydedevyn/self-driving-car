## Self Driving Car

This code represents a self-driving car simulation using the Kivy framework and artificial intelligence (AI) techniques. The car navigates a map with the goal of reaching a specific destination while avoiding sand patches. The AI algorithm controls the car's movement and decision-making process.

### Prerequisites

- Python 3.x
- Kivy framework
- NumPy library
- Matplotlib library

### Installation

1. Make sure you have Python installed on your system. If not, download and install Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

2. Install the necessary libraries by running the following command in your terminal:

   ```
   pip install -r requirements.txt
   ```

### Usage

To run the self-driving car simulation, execute the following command in your terminal:

```
python map.py
```

### Instructions

- Upon running the code, a simulation window will open showing the car and the map.

- Click and drag the left mouse button on the map to draw sand patches. The car will avoid these patches during its movement.

- The car will start moving automatically towards the goal position, which is marked by a red circle.

- The AI algorithm controls the car's movement and decision-making process. It uses three sensors to detect the presence of sand patches and adjusts the car's rotation accordingly.

- Use the "clear" button to clear the sand patches on the map.

- Use the "save" button to save the AI model's current state.

- Use the "load" button to load the last saved AI model.

### Notes

- The AI algorithm is implemented in the `ai.py` file.

- The `Dqn` class represents the AI model and its associated methods.

- The car's movement and sensor data are handled by the `Car` class.

- The game environment and overall simulation are managed by the `Game` class.

- The `MyPaintWidget` class allows drawing sand patches on the map using the left mouse button.

- The `CarApp` class creates the application and sets up the user interface.

### License

This code is licensed under the [MIT License](https://opensource.org/licenses/MIT).

### Acknowledgments

The code is based on an educational project for self-driving cars and AI. It utilizes the Kivy framework for graphical interface development and incorporates concepts from reinforcement learning.
