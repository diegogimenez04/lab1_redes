# Informe punto estrella

Las URL deben estar codificadas en ASCII para realizar el envío de la request. El programa llama a la función encode(), que permite transcribir los caracteres UTF-8 a ASCII para formar una URL válida, y así lograr el envío.

## Ejemplo 
Pasamos de “Hello Günter” lo cual no es interpretable por la ü y el espacio. Luego al codificarlo a ASCII queda “Hello%20G%C3%BCnter”.

       UTF-8                   ASCII
    http://中文.tw -> http://%E4%B8%AD%E6%96%87.tw