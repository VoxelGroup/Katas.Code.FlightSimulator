# Flight Simulator

La empresa ha recibido un encargo de un cliente muy especial y nos ha pedido realizar un simulador de vuelo.  

El simulador ha de tener en cuenta diferentes tipos de aviones:
- Avión de un solo motor “SingleEnginePlane”
- Avión de juguete “ToyPlane”
- Avión de papel “PaperPlane”  
- Hidroavion “Seaplane” 

Las comportamientos a implementar serían:
- Identificarse “Display”
- Volar “Fly”
- Aterrizar “Land” 
- Arrancar motor “StartEngine” 
  
## Implementación
- Implementa la solución de nuestro FlightSimulator utilizando **Programación Orientada a Objetos**, principios **SOLID** y teniendo en cuenta que es un cliente muy inquieto y nos va ir pidiendo ampliación de otros tipos de aviones y comportamientos continuamente y no queremos tener que tocar la implementación de los diferentes comportamientos y tipos de aviones ya implementados.

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
