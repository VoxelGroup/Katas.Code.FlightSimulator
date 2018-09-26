# Flight Simulator

La empresa ha recibido un encargo de un cliente muy especial y nos ha pedido realizar un simulador de vuelo.  

## [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product "Wikipedia Definition") (v1)
Inicialmente, se ha de entregar una primera version del simulador.
El MVP v1 del simulador ha de tener en cuenta diferentes tipos de aviones:
- Avión de un solo motor “SingleEnginePlane”
- Avión de juguete “ToyPlane”
- Avión de papel “PaperPlane”  

Las acciones a realizar serían:
- Identificarse “Display”
- Volar “Fly”
- Aterrizar “Land” 

## MVP (v2)
Una vez el MVP v1 está implementado, el cliente ve que el simulador es algo pobre y nos piden que evolucionemos el simulador a la siguiente versión, incluyendo la acción:
- Arrancar motor “StartEngine” 
  
Y añadiendo el tipo de avión:
- Hidroavion “Seaplane” 
  
Teniendo en cuenta que este tipo de avión no aterriza con ruedas.  

## Implementación
- Implementa la solución de nuestro FlightSimulator utilizando **Programación Orientada a Objetos**, principios **SOLID** y teniendo en cuenta que es un cliente muy inquieto y nos va ir pidiendo ampliación de otros tipos de aviones y comportamientos continuamente.  

## Cada metodo imprime una frase para cada tipo de avión

| Metodo      | SingleEnginePlane       | PaperPlane              | ToyPlane                    | Seaplane               |
|-------------|-------------------------|-------------------------|-----------------------------|------------------------|
| Display     | I'm a one engine plane! | I'm a paper plane!      | I'm a toy plane!            | I'm a Seaplane!        |
| StartEngine | Single engine started!  | No engine to start!     | No engine to start!         | Single engine started! |
| Fly         | Flying with real wings  | Flying with paper wings | This plane is unable to fly | Flying with real wings |
| Land        | Landing with wheels     | Crash!                  | Crash!                      | Landing with floats    |


## Para cada avión se debe llamar a los siguientes metodos en este orden:
``Display``  
``StartEngine``  
``Fly``  
``Land``  

En el caso de tratarse del SingleEnginePlane el output sera el siguiente:  

I'm a one engine plane!  
Single engine started!  
Flying with real wings  
Landing with wheels 

## Expected Output

I'm a one engine plane!  
Single engine started!  
Flying with real wings  
Landing with wheels  
  
I'm a paper plane!  
No engine to start!  
Flying with paper wings  
Crash!  
  
I'm a toy plane!  
No engine to start!  
This plane is unable to fly  
Crash!  

I'm a Seaplane!  
Single engine started!  
Flying with real wings  
Landing with floats  

---
---

## ¿Como entregar la solución?
- Preferiblemente, antes de empezar a trabajar en la solución, puedes hacer un fork de este repositorio, en tu propio usuario de GitHub. Luego has de implementar la solución en tu fork. Al finalizar, nos has de notificar por email a people@voxelgroup.net, para revisarla en tu fork.
- Alternativamente puedes de descargar la solución, implementarla offline y al finalizar, enviarla por email a people@voxelgroup.net.
