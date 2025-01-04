# Conversor de Divisas 
Challenge no. 1 del Curso "Java Orientado a Objetos" de Alura ONE 

# Contenido 
1. Descripción
2. Uso
3. Capturas
4. Tecnologías utilizadas
5. Requisitos Previos
6. Agradecimientos y créditos
7. Autor y contacto

# Descripción 
Con éste programa serás capáz de realizar conversiones entre las divisas más reelevantes de la economía mundial actualmente. 

# Uso 
Usarlo es muy sencillo e intuitivo. Para abrirlo necesitarás correr el código desde el IDE de tu preferencia y realizar los siguientes pasos: 

- Selección de divisa base: 
Se mostrarán las opciones disponibles de divisas base, que es la que quieres convertir inicialmente. El menú se verá de la siguiente forma:

-----------------------------------------------------------------
========== C O N V E R S O R     D E    D I V I S A S ==========

Divisas disponibles:
1.  Dólar Estadounidense (USD)
2.  Euro (EUR)
3.  Libra Esterlina (GBP)
4.  Yen Japonés (JPY)
5.  Dólar Canadiense (CAD)
6.  Peso Colombiano (COP)
7.  Peso Chileno (CLP)
8.  Peso Mexicano (MXN)
9.  Real Brasileño (BRL)
10. Peso Argentino (ARS)
11. Salir

¿Qué moneda desea cambiar? (Introduzca un número 1-11):

-----------------------------------------------------------------

Seleccionarás un número del 1 al 10 para elegir la divisa deseada y el 11 si deseas salir del programa. Presionas Enter para continuar.  

- Selección de divisa objetivo: 
Con la misma numeración del menú, se escogerá la divisa objetivo, que es a la cual quieres realizar la conversión y se presiona Enter. 

- Establecer monto: 
Ahora ingresarás el monto (en moneda base) que deseas convertir. Una vez ingresado el monto, presionas Enter.

¡Listo! El programa debe arrojarte los siguientes valores: 

- Resultado de la conversión. 
- Tasa de cambio (moneda base a moneda tarjet) 
- Fecha de la operación

Ahora se te preguntará si deseas continuar (S/N) 
Si ingresas "S" seguiremos realizando mas conversiones repitiendo el proceso completamente. 
Si eliges "N" el programa te avisará que el proceso ha finalizado y que tu historial de conversiones ha sido 
guardado en un archivo .JSON

# Capturas 
![Captura_1](https://github.com/MontesX/Conversor_Alura_Challenge/blob/c9837e10b4cd353366f1231e4bef603c4fc3afa1/captura_1.JPG)

![Captura_2](https://github.com/MontesX/Conversor_Alura_Challenge/blob/c9837e10b4cd353366f1231e4bef603c4fc3afa1/captura_2.JPG)

![Captura_3](https://github.com/MontesX/Conversor_Alura_Challenge/blob/c9837e10b4cd353366f1231e4bef603c4fc3afa1/captura_3.JPG)

# Tecnologías Utilizadas
Para la elaboración de éste proyecto se utilizaron las siguientes herramientas y lenguajes. 

- Java 17 como lenguaje
- Consumo de API desde [Exchange Rate API](https://www.exchangerate-api.com/)
- Librería GSON
- Trello

# Requisitos Previos 
* Librería [Gson 2.11.0](https://mvnrepository.com/artifact/com.google.code.gson/gson/2.11.0)
* API Key proporcionada por ExchangeRate-API, reemplazar valor de variable de entorno por su propia API

# Agradecimientos y Créditos
Con total agradecimiento a mis tutores: 
Por brindarnos su tiempo, su atención, y hacer posible ésta formación en progreso. ¡Muchas gracias!
- [Oracle](https://www.oracle.com/ar/education/oracle-next-education/)
- [Alura Latam](https://app.aluracursos.com/form-one/registro/latam-general)

# Autor
Desarrollado por Paul Montes.

Contacto: 
- [LinkedIn](https://www.linkedin.com/in/montessx/)

