### Tarde para el vuelo?

- Al tomar un vuelo en avion necesitamos estar 3hrs antes del vuelo, con Check-in realizado, entregar el equipaje y tarjeta de embarque impreso o digital 
    - Solicitar requerimientos al pasajero e informar estado de su vuelo
        - Requerimientos:
            1. Hora de salida del vuelo
            1. Hora de llegada al aeropuerto
            1. Estado del Check-in
            1. Estado de la entrega del equipaje
            1. Posee tarjeta de embarque impresa
            1. Posee tarjeta de embarque  digital
    - Simular dicha operacion con un diagrama de flujo y pseudocodigo
    - Ejemplo de resultado final CON todos los requerimientos:
        ```
        ###Estado de vuelo###

        3hrs antes del vuelo: VERDADERO
        con check-in: VERDADERO
        equipaje entregado: VERDADERO
        tarjeta impresa o digital: VERDADERO

        Cumple con los requerimientos: VERDADERO
        ``` 
     - Ejemplo de resultado final SIN todos los requerimientos:
        ```
        ###Estado de vuelo###

        3hrs antes del vuelo: FALSO
        con check-in: VERDADERO
        equipaje entregado: VERDADERO
        tarjeta de embarque: VERDADERO

        Cumple con los requerimientos: FALSO
        ``` 