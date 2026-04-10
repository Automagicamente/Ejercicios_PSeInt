### PedidosCode

- Implementar un menu automatizado que permita al usuario solicitar un pedido mediante nuestra app
    - Los pedidos se diferencian por Comida rapida/Supermercado/Farmacia y una vez seleccionado el tipo dependiendo del mismo se tendran diferentes opciones:
        - Comida rapida
            1. Pizza
            1. Hamburguesa
        - Supermercado
            1. Papel Higienico
            1. Harina
        - Farmacia
            1. Medicamento
            1. Curitas
    - Luego de seleccionar el tipo y opcion, correspondiente al pedido, es necesario solicitar medio de pago:
        1. Efectivo
        1. Tarjeta
            - En este caso tiene que accionarse un sub menu para debito o credito (no se consideran las cuotas)
    - Simular dicha operacion con un diagrama de flujo y pseudocodigo
    - Ejemplo 1 de resultado final:
        ```
        ### Iniciando pedido ###

        Tipo de pedido: Supermercado
        Pedido: Papel higienico
        Medio de pago: TarjetaCredito

        Pedido iniciado...
        ``` 
        
    - Ejemplo 2 de resultado final:
        ```
        ### Iniciando pedido ###

        Tipo de pedido: Farmacia
        Pedido: Curitas
        Medio de pago: Efectivo

        Pedido iniciado...
        ``` 
    
    <br>

    - Requisito extra
        - Considerar cuotas para tarjeta de credito (1/3/6)
        - Ejemplo de resultado final:
            ```
            ### Iniciando pedido ###

            Tipo de pedido: Farmacia
            Pedido: Curitas
            Medio de pago: TarjetaCredito - 3 Cuotas

            Pedido iniciado...
            ``` 