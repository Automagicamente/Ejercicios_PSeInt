- Crear un programa que permita Actualizar una tarea especifica como **terminada** de un determinado **_Y_** día de la semana

    - Cada tarea tiene propiedades de:
        1. Titulo
        1. Fecha creacion
        1. Terminada
            - `false` por defecto

    - Tareas disponibles:
        - Lunes:
            1. Lavar ropa
            1. Jugar con mascota
        - Miercoles:
            1. Ordenar cuarto
            1. Ejercicio
            
    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        L
                ***Mostrando tareas del día Lunes**
            1- Lavar ropa
            2- Jugar con mascota
        
        Seleccione una tarea a actualizar como Terminada?
        1

        ### Actualizando la tarea 'Lavar ropa' del día Lunes como Terminada ###

        [
            [
                { titulo: 'Lavar ropa', fechaInicio: '10/10/2010', terminada: true },
                { titulo: 'Jugar con mascota', fechaInicio: '10/10/2010', terminada: false }
            ],
            [],
            [
                { titulo: 'Ordenar cuarto', fechaInicio: '10/10/2010', terminada: false },
                { titulo: 'Ejercicio', fechaInicio: '10/10/2010', terminada: false }
            ],
            [],
            [],
            [],
            []
        ]

        ``` 