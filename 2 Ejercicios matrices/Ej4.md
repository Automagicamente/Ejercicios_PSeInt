- Crear un programa que permita Actualizar una tarea especifica a **Completada** de un determinado **_Y_** día de la semana
    - Tareas disponibles:
        - Lunes:
            1. Lavar ropa
            1. Jugar con mascota
        - Miercoles:
            1. Ordenar cuarto
            1. Cocinar
            1. Ejercicio
        - Viernes:
            1. Practicar programacion
    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        L
                ***Mostrando tareas del día Lunes**
            1- Lavar ropa
            2- Jugar con mascota
        
        Que tarea desea marcar como Completada?
        1

        ### Completando tarea Nº1 del día Lunes ###

        [["Lavar ropa - Completada", "Jugar con mascota"],[],["Ordenar cuarto", "Cocinar", "Ejercicio"],[],["Practicar programacion"],[],[]]

        ``` 
    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        Mi
                ***Mostrando tareas del día Miercoles**
            1- Ordenar cuarto
            2- Cocinar
            3- Ejercicio

        
        Que tarea desea marcar como Completada?
        2

        ### Completando tarea Nº1 del día Miercoles ###

        [["Lavar ropa", "Jugar con mascota"],[],["Ordenar cuarto", "Cocinar - Completada", "Ejercicio"],[],["Practicar programacion"],[],[]]

        ``` 