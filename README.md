#  Servidores -Welcome World 🌐🗺️🚀


Este repositorio contiene el código fuente de la aplicación web desarrollada para el desafío Servidores Welcome World.
En este desafío validaremos nuestros conocimientos de CRUD de archivos con File System, además de verbos
y parámetros para consultas HTTP y formularios HTML y servidores con Express. 
Para lograrlo, necesitarás utilizar de apoyo el archivo Apoyo Desafío - Servidores Welcome World 

## Descripción de la solución 💻

La compañía Welcome World Spa se dedica a ofrecer servidores y paneles de control con herramientas de FTP. La compañía necesita agregar una funcionalidad que le permita a sus
usuarios crear dentro de la plataforma los archivos con las extensiones y el contenido que deseen, el mismo debe ser almacenado en el servidor.
Necesitarás crear un servidor con Express que permita crear, leer, renombrar y eliminar archivos alojados en el servidor por medio de las rutas correspondientes.
Deberás enviar los datos como parámetros en una consulta GET por medio de formularios HTML. 
Siéntete libre de crearlo si así lo prefieres o usar el del Apoyo Desafío, el cual contiene lo que verás en la siguiente imagen.

## Requerimientos 

1. Disponibilizar una ruta para crear un archivo a partir de los parámetros de la consulta
recibida (2 Puntos)
2. Disponibilizar una ruta para devolver el contenido de un archivo cuyo nombre es
declarado en los parámetros de la consulta recibida (2 Puntos).
3. Disponibilizar una ruta para renombrar un archivo, cuyo nombre y nuevo nombre es
declarado en los parámetros de la consulta recibida (2 Puntos).
4. Disponibilizar una ruta para eliminar un archivo, cuyo nombre es declarado en los
parámetros de la consulta recibida (2 Puntos).
5. Devolver un mensaje declarando el éxito o fracaso de lo solicitado en cada consulta
recibida (2 Puntos).
6. Agrega la fecha actual al comienzo del contenido de cada archivo creado en formato
“dd/mm/yyyy”. Considera que si el día o el mes es menor a 10, concatenar un “0” a la
izquierda. (Opcional)
7. En la ruta para renombrar, devuelve un mensaje de éxito, incluyendo el nombre anterior
del archivo y su nuevo nombre de forma dinámica. (Opcional)

Siguiendo esta gráfica: 




## Estructura del Proyecto 🩻

El proyecto está estructurado de la siguiente manera:

![image](https://github.com/CamiSerantoni/servidoresWlcomeWorld/assets/152921799/d9098656-5563-401a-96f9-74619ec722cc)

## Vista: 

La solución se ve de la siguiente manera: 

![image](https://github.com/CamiSerantoni/servidoresWlcomeWorld/assets/152921799/c589bed1-5d68-4f5f-a185-71f8de279965)


## Dependencias 🪢

El proyecto utiliza las siguientes dependencias principales:

- **Express**: Para la creación del servidor web.

## Requisitos y Configuración 🔩🛠️🧰

Para ejecutar el proyecto localmente, asegúrate de tener instalado Node.js y npm. Luego, sigue estos pasos:

1. Clona este repositorio: `git clone <URL_del_repositorio>`
2. Accede al directorio del proyecto: `cd <nombre_del_directorio>`
3. Instala las dependencias del proyecto: `npm install`
4. Inicia el servidor local: `npm run dev`
5. Abre tu navegador web y accede a `http://localhost:3000` para ver la aplicación en funcionamiento.

## Integrante: 😺

- Camila Serantoni R. 
