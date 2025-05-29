- Crear un programa que permita Agregar X cantidad de tareas en Y dia de la semana
    
    - Cada tarea tiene propiedades de:
        1. Titulo
        1. Fecha creacion
        1. Terminada

    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        L
        Cuantas tareas deseas agregar?
        3

        ### Agregando 3 tareas al dia Lunes ###
            Lavar ropa
            Ordenar cuarto
            Practicar programacion
        ### Tareas agregadas ###

        [
            [
                { titulo: 'Lavar ropa', fechaInicio: '11/3/2023', terminada: false },
                { titulo: 'Ordenar cuarto', fechaInicio: '7/2/2025', terminada: true },
                { titulo: 'Practicar programacion', fechaInicio: '23/5/2024', terminada: false }
            ],
            [],
            [],
            [],
            [],
            [],
            []
        ]

        ``` 