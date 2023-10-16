# CreatePublishRun

Este es un proyecto simple de UiPath que muestra un mensaje "Hello World!" en una ventana emergente que se cierra automaticamente.

## Código 

El código consiste en:

- Un workflow con un sequence que contiene las actividades:
  - LogMessage - Registra un mensaje "Start"
  - MessageBox - Muestra el mensaje "Hello World!"
  - Delay - Espera 5 segundos
  - LogMessage - Registra un mensaje "End"

## Funcionamiento

Al ejecutar el robot de UiPath:

1. Se registra el mensaje "Start" en el log de UiPath
2. Se muestra el mensaje "Hello World!" en una ventana emergente 
3. Después de 5 segundos, el mensaje se cierra
4. Se registra el mensaje "End" en el log de UiPath

Por lo tanto, el robot muestra el mensaje por 5 segundos y luego registra que el proceso finalizó.

## Requisitos

- UiPath.System.Activities 23.4.3 

