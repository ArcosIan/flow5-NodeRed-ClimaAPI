# flow5-NodeRed-ClimaAPI
Este repositorio contiene el flow de NodeRed para obtener la informacion climatica por API desde openweathermap.org

# Introducción
Este flow consiste en un tablero que presente la información de temperatura y humedad por medio de APIS a traves de openweathermap.

# Material Necesario
Para realizar este flow necesitas lo siguiente

   [Ubuntu 20.04](https://releases.ubuntu.com/20.04/) 
  
   [ NodeJS](https://nodejs.org/es/)
   
   [ NPM](https://www.npmjs.com/)
       
   [NodeRed](https://nodered.org/docs/getting-started/local)
        
   [  Nodos Dashboard](https://flows.nodered.org/node/node-red-dashboard)
   
  [ OpenWeatherMap]([https://openweathermap.org/api)
  
  # Material de referencia
En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realiar las configuraciones necesarias



   [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
   
   [Instalación de NodeRed](https://edu.codigoiot.com/enrol/index.php?id=817)
   
   [Introducción a NodeRed](https://edu.codigoiot.com/enrol/index.php?id=278)
   
   # Instrucciones
Requisitos previos
Para que este flow funcione, debes cumplir con los siguientes requisitos previos

Instalación de NodeJS. Se recomienda tener instalado NodeJS en alguna versión LTS. Al momento de creación de este documento, se usó la versión 16.17.0LTS. Esta instalación debe incluir las Build-Tools para hacer uso de NPM


Instalación de NodeRed. La instalación se realiza por NPM. Al momento de la creación de este contenido, se usó la versión 3.0.2


Instalar los nodos node-red-dashboard. Para ello, dirigete a la opcion "Manage Palet" de NodeRed y en la pestaña Install busca node-red-dashboard. Finalmente haz clic en instalar.

Instalación de la API


Instrucciones de preparación del entorno
Para ejecutar este flow, es necesario lo siguiente

Arrancar NodeRed con el comando node-red

Importar el flow del repositorio

Hacer clic en el boton Deploy

Instrucciones de operación

Para observar el resutlado de este flow, abre un navegador y dirígete a localhost:1880/ui
    
Notas
Las cordenadas deberan de ser cambiadas para poder mostar una diferente ubicación

Es importante registarse en OpenWeatherMap para generar nuestra API KEY 

Ejemplo de como hacer una llamada a la API

Llamada general
https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}&units=metric 

# Resultados
A continuación puedes ver los nodos del flow.![Captura de pantalla del flow 5](https://user-images.githubusercontent.com/111370977/187746764-f7ddba6f-e24e-4085-993b-3e45c8c111ad.png)



A continuación puede ver el tablero resultante.
![Captura de pantalla del flow 5-2](https://user-images.githubusercontent.com/111370977/187746811-6668ef8c-65e1-4f1a-8308-2170bf34c474.png)


# Evidencias




https://user-images.githubusercontent.com/111370977/187748052-08aede76-f235-4f62-86e2-082be6de9cd2.mp4








# Creditos




Desarrollado por Ian Arcos

https://github.com/ArcosIan
