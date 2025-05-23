- Crear un programa que permita mostrar **_X_** cantidad de tareas dependiendo de **_Y_** día de la semana 

    - Cada tarea tiene propiedades de:
        1. Titulo
        1. Fecha creacion
            - Por defecto la actual
        1. Terminada

    - Lista de tareas inicial: 
        - Lunes: Lavar ropa
        - Miercoles: Ordenar cuarto
        - Sabado: Practicar programacion
        - Resto de días sin tareas inicialmente

    - Ejemplo de resultado:
        ```
        Ingrese inicial del día a revisar tareas L-M-Mi-J-V-S-D?
        L
        ### Mostrando 1 tarea/s del día Lunes ###

            Tarea Nº 1:
                - Lavar ropa
                - 25/5/2025
                - Sin terminar

        ### Fin de tareas ###
        ``` 
    - Ejemplo de resultado:
        ```
        Ingrese inicial del día a revisar tareas L-M-Mi-J-V-S-D?
        V
        ### Mostrando 1 tarea/s del día Viernes ###

            Tarea Nº 1: 
                - Practicar programacion
                - 25/5/2025
                - Sin terminar

        ### Fin de tareas ###
        ``` 