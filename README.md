# Multiplicar Console App

Aplicación para generar archivos de tablas de multiplicar en .txt basado en Node. Ejercicio de curso.

## Pasos previos

Ejecutar ```$ npm install``` para instalar liberías.

## Comandos

| **Comando / Parámetro** | **Descripción** | **Ejemplo**|
| ------ | ------ | ------ |
| listar | Imprime en consola la tabla de multiplicar | - |
| &nbsp;&nbsp;&nbsp;&nbsp;--base, -b | *[Requerido]* Establece el multiplicador de la operación | ```$ node app listar -b 5``` |
| &nbsp;&nbsp;&nbsp;&nbsp;--limite, -l | *[Opcional - Default: 10]* Establece el límite de la iteración del multiplicando | ```$ node app listar -b 5 -l 50``` |
| crear | Crea el archivo con la tabla de multiplicar en el directorio de tablas dentro del proyecto | - |
| &nbsp;&nbsp;&nbsp;&nbsp;--base, -b | *[Requerido]* Establece el multiplicador de la operación | ```$ node app listar -b 5``` |
| &nbsp;&nbsp;&nbsp;&nbsp;--limite, -l | *[Opcional - Default: 10]* Establece el límite de la iteración del multiplicando | ```$ node app listar -b 5 -l 50``` |
| --help | Muestra la ayuda | ```$ node app --help``` |