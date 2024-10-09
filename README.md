# IEBS_-Sprint1
Contrato en Solidity para el sprint de Programación

Sprint1

Smart Contracts:

    SimpleStorage: tiene funciones de añadir/modificar numero, leer numero y de retrieve amount spended al wallet que llame la funcion.
    OtherStorage: tiene exactamente las mismas funciones, solo que las llama desde el otro contrato :)

Remix:

    Despues de compilar los dos contratos, realizaremos las siguientes acciones:

        SimpleStorage:
            Llamar addFavNumb: al llamar a esta funcion deberemos pagar algo. No puede ser menos o igual a 0. Una vez pagado podremos añadir/modificar un nuevo numero
            Llamar getFavNumb: al llamar a este funcion obtendremos el numero.
            Llamar retrieveAmount: al llamar a esta funcion obtendremos de vuelta la cantidad invertida para crear/modificar numeros.

        OtherStorage:
            Llamamos exactamente a las mismas funciones que en SimpleStorage y recibimos exactamente los mismos resultados. Es decir, usamos un contrato desde otro contrato.

Etherscan:
