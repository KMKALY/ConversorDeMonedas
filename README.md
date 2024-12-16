# Conversor de Monedas

Este es un proyecto de un conversor de monedas que permite convertir entre diversas divisas de forma rápida y sencilla. Utiliza una API externa para obtener las tasas de cambio más recientes y realizar las conversiones en tiempo real.

## Características

- Conversión entre varias monedas: Dólar, Peso Argentino, Real Brasileño, Euro, entre otras.
- API externa para obtener tasas de cambio en tiempo real.
- Interfaz de consola sencilla de usar.
- Manejo de errores de red y entrada del usuario.

## Tecnologías utilizadas

- **Java**: Lenguaje principal para el desarrollo del proyecto.
- **API externa**: Se utiliza para obtener las tasas de cambio actuales.
- **Dotenv**: Para gestionar las claves API de forma segura.

## Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio:
 Abre la terminal donde quieras que se guarde el repositorio con git bash y ejecuta el siguiente comando para clonar el proyecto desde GitHub:
   ```bash
   git clone https://github.com/KMKALY/ConversorDeMonedas.git
   ```   
2. Entra en el directorio del proyecto:
   ```bash
   cd ConversorDeMonedas
   ```
3. Configura el archivo .env
- Crea un archivo llamado .env en la raíz del proyecto y añade la siguiente línea con tu clave de API:
   ```bash
EXCHANGE_RATE_API_KEY=tu-api-key-aqui
   ```
4. Ejecuta el programa:
Asegúrate de tener Java instalado en tu máquina. Luego, ejecuta el programa con:
   ```bash
java -jar ConversorDeMonedas.jar
   ```

**Uso**
1- Al ejecutar el programa, se te presentará un menú con las opciones de conversión disponibles.
2- Selecciona el número correspondiente a la conversión que deseas realizar.
3- Ingresa el monto a convertir.
4- Obtendrás el resultado en tiempo real con la tasa de cambio actual.