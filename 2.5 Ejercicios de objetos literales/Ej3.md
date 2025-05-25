- Crear un programa que permita Eliminar una propiedad de una tarea especifica en un **_Y_** día de la semana

    - Cada tarea tiene propiedades de:
        1. Titulo
        1. Fecha creacion
            - Por defecto la actual
        1. Terminada

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
        
        Seleccione una tarea?
        1

        Propiedades en Lavar ropa:
            1- titulo: Lavar ropa
            2- fechaInicio: 10/10/2010
            3- terminada: false
        Que propiedad necesitas eliminar ?
        2   
        ### Eliminando propiedad 'fechaInicio' del día Lunes ###

        [
            [
                { titulo: 'Lavar ropa', terminada: false },
                { titulo: 'Jugar con mascota', fechaInicio: '10/10/2010', terminada: false }
            ],
            [],
            [
                { titulo: 'Ordenar cuarto', fechaInicio: '10/10/2010', terminada: false },
                { titulo: 'Ejercicio', fechaInicio: '10/10/2010', terminada: true }
            ],
            [],
            [],
            [],
            []
        ]

        ``` 
    - Ejemplo de resultado:
        ```
        Seleccione dia a modificar:  L-M-Mi-J-V-S-D
        Mi
                ***Mostrando tareas del día Miercoles**
            1. Ordenar cuarto
            2. Ejercicio
        
        Seleccione una tarea?
        2

        Propiedades en Lavar ropa:
            1- titulo: Lavar ropa
            2- fechaInicio: 10/10/2010
            3- terminada: false
        Que propiedad necesitas eliminar ?
        3   
        ### Eliminando propiedad 'terminada' del día Miercoles ###

        [
            [
                { titulo: 'Lavar ropa', terminada: false },
                { titulo: 'Jugar con mascota', fechaInicio: '10/10/2010', terminada: false }
            ],
            [],
            [
                { titulo: 'Ordenar cuarto', fechaInicio: '10/10/2010', terminada: false },
                { titulo: 'Ejercicio', fechaInicio: '10/10/2010'}
            ],
            [],
            [],
            [],
            []
        ]

        ``` 

---

<br>
<br>
<br>
<br>

- Extras
    1. Investigar como evitar que un objeto literal sea alterado una vez creado en todas sus propiedades
    1. Investigar como evitar que _**solo**_ algunas de las propiedades de un objeto literal sean eliminadas