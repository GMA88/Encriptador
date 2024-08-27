# Encriptador de Textos

## Descripción

Este proyecto es una aplicación web simple que permite encriptar y desencriptar textos utilizando un conjunto de reglas específicas. La aplicación está diseñada para intercambiar mensajes secretos, donde solo aquellos que conocen la clave de encriptación podrán entender el mensaje original.

### Reglas de Encriptación:

Las siguientes reglas se utilizan para encriptar las vocales en el texto:

- La letra "e" se convierte en "enter".
- La letra "i" se convierte en "imes".
- La letra "a" se convierte en "ai".
- La letra "o" se convierte en "ober".
- La letra "u" se convierte en "ufat".

Por ejemplo:
- "gato" se convierte en "gaitober".
- "gaitober" se desencripta nuevamente a "gato".

## Características

- **Encriptación y Desencriptación**: La aplicación permite convertir un texto a su versión encriptada y también devolver un texto encriptado a su versión original.
- **Interfaz de Usuario Simple**: La aplicación tiene una interfaz de usuario sencilla con campos para ingresar el texto y botones para realizar la encriptación, desencriptación y copiar el resultado.
- **Copiado al Portapapeles**: Un botón adicional permite copiar el texto encriptado o desencriptado al portapapeles para un uso más fácil.

## Requisitos

- La aplicación solo funciona con letras minúsculas.
- No se deben utilizar letras con acentos ni caracteres especiales.

## Estructura del Proyecto

- `index.html`: El archivo HTML principal que contiene la estructura básica de la aplicación.
- `script.js`: El archivo JavaScript que contiene la lógica de encriptación, desencriptación y copiado al portapapeles.

## Instrucciones de Uso

1. **Abrir el archivo `index.html`** en un navegador web.
2. **Escribir el texto** que deseas encriptar o desencriptar en el área de texto superior.
3. Hacer clic en **"Encriptar"** para convertir el texto a su versión encriptada o en **"Desencriptar"** para revertir el texto encriptado a su versión original.
4. El resultado se mostrará en el área de texto inferior.
5. **Hacer clic en "Copiar"** para copiar el resultado al portapapeles.
