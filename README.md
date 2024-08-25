# Pokemon_QC
Integración de obtención de datos de un Pokémon con una operación cuántica.

[![25.png](https://i.postimg.cc/mhfWdXdh/25.png)](https://postimg.cc/RJRYhRxz)
[![422.png](https://i.postimg.cc/vHhc15Df/422.png)](https://postimg.cc/tY1XwZ34)
[![132.png](https://i.postimg.cc/KYnfL9TJ/132.png)](https://postimg.cc/kVgWPvfb)

# Indicaciones en Español
# Recuperación de Datos de Pokémon y Toma de Decisiones con Computación Cuántica

Este proyecto demuestra cómo recuperar datos de un Pokémon utilizando la PokeAPI y cómo tomar una decisión basada en principios de computación cuántica utilizando Qiskit.

## Características

- **Recuperación de Datos de Pokémon**: La aplicación obtiene detalles como nombre, peso, altura, tipos, habilidades y una URL de imagen para un nombre de Pokémon dado usando la PokeAPI.
- **Toma de Decisiones Cuántica**: Utiliza Qiskit de IBM para simular la toma de decisiones cuánticas sobre si guardar o no los datos del Pokémon.
- **Interfaz Gráfica de Usuario (GUI)**: Integración de PyQt6 para proporcionar una interfaz simple para ingresar el nombre del Pokémon y mostrar los datos recuperados y la decisión cuántica.

## Requisitos

- Python 3.x
- Qiskit
- PyQt6
- Requests (para llamadas a la API)

## Cómo Ejecutar

1. Asegúrate de que todos los paquetes requeridos estén instalados:

    ```bash
    pip install qiskit pyqt6 requests
    ```

2. Ejecuta la aplicación:

    ```bash
    python pokemon_qiskit.py
    ```

3. Aparecerá una GUI solicitando el nombre del Pokémon. Ingresa el nombre y la aplicación mostrará los datos recuperados junto con la decisión cuántica.

## Explicación del Código

### Secciones Principales

- **Recuperación de Datos (`obtener_datos_pokemon`)**: Recupera datos de la PokeAPI para el Pokémon especificado.
- **Decisión Cuántica (`decidir_con_computacion_cuantica`)**: Utiliza Qiskit para decidir si los datos deben ser guardados.
- **Integración de GUI**: Se utiliza PyQt6 para crear una interfaz de usuario amigable para la entrada y salida de datos.
- **Almacenamiento de Datos (`guardar_datos_pokemon`)**: Si la decisión cuántica es positiva, los datos se guardan como un archivo JSON.

### Computación Cuántica

La decisión de guardar los datos del Pokémon se basa en un circuito cuántico simulado. Se analizan los resultados y, si se cumple una cierta condición (por ejemplo, que el resultado '1' se mida más de 400 veces), los datos se guardan.

## Conclusión

Este proyecto combina la interacción clásica con una API y la computación cuántica, demostrando cómo los principios cuánticos pueden integrarse en aplicaciones cotidianas.

## Imagenes de ejemplo de la ejecución

[![torterra.jpg](https://i.postimg.cc/NF8gCY72/torterra.jpg)](https://postimg.cc/XBJSXRPn)
[![information-Torterra.jpg](https://i.postimg.cc/yYXmcZ9s/information-Torterra.jpg)](https://postimg.cc/2VyLf32K)
[![dato-Guardado-Torterra.jpg](https://i.postimg.cc/LXK5xyK7/dato-Guardado-Torterra.jpg)](https://postimg.cc/sBm3X429)



# Indicaciones en Ingles
# Pokémon Data Retrieval and Quantum Computing Decision-Making

This project demonstrates how to retrieve data for a Pokémon using the PokeAPI and how to make a decision based on quantum computing principles using Qiskit.

## Features

- **Pokémon Data Retrieval**: The application fetches details such as name, weight, height, types, abilities, and an image URL for a given Pokémon name using the PokeAPI.
- **Quantum Decision Making**: Utilizes IBM's Qiskit to simulate quantum decision-making on whether to save the Pokémon data or not.
- **Graphical User Interface (GUI)**: Integrated PyQt6 to provide a simple interface for entering the Pokémon name and displaying the retrieved data and quantum decision.

## Requirements

- Python 3.x
- Qiskit
- PyQt6
- Requests (for API calls)

## How to Run

1. Ensure that all the required packages are installed:

    ```bash
    pip install qiskit pyqt6 requests
    ```

2. Run the application:

    ```bash
    python pokemon_qiskit.py
    ```

3. A GUI will appear asking for the Pokémon name. Enter the name and the application will display the retrieved data along with the quantum decision.

## Code Explanation

### Main Sections

- **Data Retrieval (`obtener_datos_pokemon`)**: Fetches data from the PokeAPI for the specified Pokémon.
- **Quantum Decision (`decidir_con_computacion_cuantica`)**: Uses Qiskit to decide if the data should be saved.
- **GUI Integration**: PyQt6 is used to create a user-friendly interface for input and output.
- **Data Storage (`guardar_datos_pokemon`)**: If the quantum decision is positive, the data is saved as a JSON file.

### Quantum Computing

The decision to save the Pokémon data is based on a simulated quantum circuit. The results are analyzed, and if a certain condition is met (e.g., the result '1' is measured more than 400 times), the data is saved.

## Conclusion

This project combines classical API interaction with quantum computing, demonstrating how quantum principles can be integrated into everyday applications.

[![25.png](https://i.postimg.cc/mhfWdXdh/25.png)](https://postimg.cc/RJRYhRxz)
[![422.png](https://i.postimg.cc/vHhc15Df/422.png)](https://postimg.cc/tY1XwZ34)
[![132.png](https://i.postimg.cc/KYnfL9TJ/132.png)](https://postimg.cc/kVgWPvfb)
