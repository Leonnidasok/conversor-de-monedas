# challenge-conversor-divisas
Challenge conversor de divisas en tiempo real utilizando
API de conversión.

## Descripción 
Este proyecto permite convertir cantidades de una moneda a otra utilizando una API de conversión.
El usuario introduce el codigo de la moneda de origen, el codigo de la moneda de destino y la cantidad a convertir. 
El programa entonces consulta la API para obtener el factor de conversión y muestra el resultado final.

## Caracteristicas
1. Conversion de monedas en tiempo real.
2. Utiliza API de conversión para obtener factores precisos.
3. Interfaz facil de usar.
4. Compatible con multiples monedas.

## Requisitos
1. Java 17 o superior.
2. Conexion a internet para consultar API.

## Uso
1. Clona el repositorio
2. Compila el proyecto utilizando Maven o Gradle.
3. Ejecuta el programa.

![image](https://github.com/user-attachments/assets/22bbee3c-7f02-4ecc-b6e9-19b8eca052f5)

   
4. Introduce el codigo de la moneda de origen (ej. USD, UYU, etc.)
5. Introduce el codigo de la moneda de destino (ej. MXN, EUR, etc.)
6. Introduce la cantidad a convertir (ej. 1000)

![image](https://github.com/user-attachments/assets/a6e6f043-5104-4177-a455-724e4430d028)


7. El programa muestra el resultado final y pregunta si desea realizar otra operación, regresando al punto 4.-

![image](https://github.com/user-attachments/assets/60a230c2-8a34-443c-bdbe-334552f479a4)

8. En caso que se seleccione "no", finaliza el programa.

![image](https://github.com/user-attachments/assets/fcc873ae-0497-48c1-a9b4-b3884e59223d)


## API utilizada
[ExchangeRate-API](https://v6.exchangerate-api.com/)