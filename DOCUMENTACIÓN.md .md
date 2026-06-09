## 1. ¿Qué es Git?


Git es una plataforma que nos permite tener un control de versiones en un repositorio, generalmente esta en la nube. Su función principal es registrar los cambios realizados en los archivos de un proyecto para que varios usuarios puedan colaborar sin perder información.


## 2. Flujo de trabajo de Git
El flujo de trabajo se basa en la sincronización de tres estados:
Directorio Local: La carpeta de nuestro ordenador donde realizamos los cambios físicos en los archivos. 
Repositorio Local: Espacio donde se guardan los cambios de forma segura en nuestro equipo antes de enviarlos al servidor. 
Repositorio Remoto: Carpeta sincronizada en la nube que contiene todos los cambios subidos por todos los usuarios.

## 3. Comandos realizados durante la práctica
Git Add: Prepara los archivos del directorio local para ser registrados.


Git Commit: Sube los cambios del directorio local al repositorio local. 


Git Push: Envía los cambios guardados en el repositorio local al repositorio remoto en el servidor. 


Git Pull: Descarga e integra todos los cambios del repositorio remoto directamente en nuestro directorio local. 


Git Fetch: Consulta los cambios que hay en el servidor sin descargarlos todavía al directorio de trabajo.


Git Merge: Une dos ramas o versiones diferentes de un código para combinar el trabajo que hagamos.


 En la práctica se utiliza Sourcetree como interfaz gráfica para facilitar estos procesos.


## 4. ¿Qué es un conflicto de Git, qué lo causa y cómo podemos solucionarlo?
Un conflicto ocurre cuando intentamos hacer un push y Git detecta que el mismo archivo ha sido modificado en la misma línea por otra persona.


Ante un conflicto decidimos que tiene prioridad: 


Quedarnos con nuestros cambios (HEAD). 


Quedarnos con los cambios del repositorio (MASTER). 


Mantener ambos

![alt text](image.png)
En la imagen se está gestionando cambios de código.
