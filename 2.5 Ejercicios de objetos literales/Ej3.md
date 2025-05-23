- Crear un programa que permita Eliminar una propiedad de una tarea especifica en un **_Y_** día de la semana

    - Cada tarea tiene propiedades de:
        1. Titulo
        1. Fecha creacion
            - Por defecto la actual
        1. Terminada

    - Tareas disponibles:
        - Lunes:
            1. Jugar con mascota
        - Miercoles:
            1. Ordenar cuarto
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

        Propiedades en Lavar ropa:
            1- titulo: Lavar ropa
            2- fechaInicio: 23/5/2025
            3- terminada: false
        Que propiedad necesitas eliminar ?
        2   
        ### Eliminando propiedad fechaInicio del día Lunes ###

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