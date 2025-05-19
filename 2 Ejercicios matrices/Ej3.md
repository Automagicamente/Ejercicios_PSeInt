- Crear un programa que permita Eliminar una tarea especifica de un **_Y_** día de la semana
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
        
        Que tarea desea eliminar?
        1

        ### Eliminando tarea Nº1 del día Lunes ###

        [["Jugar con mascota"],[],["Ordenar cuarto", "Cocinar", "Ejercicio"],[],["Practicar programacion"],[],[]]

        ``` 
    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        Mi
                ***Mostrando tareas del día Miercoles**
            1- Ordenar cuarto
            2- Cocinar
            3- Ejercicio

        
        Que tarea desea eliminar?
        2

        ### Eliminando tarea Nº2 del día Miercoles ###

        [["Lavar ropa", "Jugar con mascota"],[],["Ordenar cuarto", "Ejercicio"],[],["Practicar programacion"],[],[]]

        ``` 