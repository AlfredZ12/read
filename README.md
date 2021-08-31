Ver en [Git-HuB](https://github.com/AlfredZ12/read)

# English_System
## Instalar Node.js, npm y Angular en el equipo 
### Descargar [node 14.17.5 LTS](https://nodejs.org/es/)
* Verificar la instalacion con el siguiente comando en cmd o bash de linux
```bash
    node -v
``` 
### instalar npm 
```bash
   npm install npm@latest -g
``` 
* Verificamos la instalacion
```bash
   npm --v
``` 
### instalar Angular
```bash
   npm install -g @angular/cli 
``` 
* verificamos la instalacion.
```bash
  ng --help 
``` 

# Instalacion de Servidor y Cliente
## Client
### Instalacion Client
  * En cmd de windows o bash de linux ingresar a la ruta de la carpeta cliente. Ejemplo C:\User\TU_NOMBRE_US\Escritorio\English_System\client

   ```bash
 
  C:\User\TU_NOMBRE_US\Escritorio>  cd English_System\client
 
  ```
  * Dentro de la carpeta instalar dependencias desde cmd 
    ```bash
    
    npm install
    
    ```
  * una vez instalados ejecutar el siguiente comando para verlo desde entorno de desarrollo, la ruta por defecto es [localhost:4200](localhost:4200)

    ```bash
    
    ng serve -o
    
    ```

   * para ponerlo en modo produccion ejecutar el siguiente comando

      ```bash
      
      ng build --prod 
      
      ```
   * Puedes usar wamp o xampp para verificarlo en produccion, copiando la carpeta que esta dentro de la carpeta dist generada por @angular/cli y copearla a la carpeta que sirve apache desde wamp o xammp ejemplo, en wampp C:\wamp64\www y entrar la localhost:8080\el_nombre_delacarpeta y estara en produccion desde apache 

   **Para poder utilizar debes configurar el servidor primero**  




## Server, Escrito en Node.js

### Instalacion Server
  * En cmd de windows o bash de linux ingresar a la ruta de la carpeta server. Ejemplo C:\User\TU_NOMBRE_US\Escritorio\English_System\server

    ```bash
    
      C:\User\TU_NOMBRE_US\Escritorio>  cd English_System\server
    
    ```
 * Dentro de la carpeta instalar dependencias desde cmd 
    ```bash
    
    npm install
    
    ```

* Correr Servidor con el siguiente comando 

    ```
    npm start
    ```
* puedes verficar que el servidor esta funcionando en el navegador o gestor de de Peticiones http como POSTMAN, Cabe mencionar que pedira un registro con un token de autenticacion por lo que recomendaria postman.

* [localhost:1899](localhost:1899)

## Construido con:

* [node.js]() - Framework Web
* [TypeScript]() - Backend
* [Express.js]() - Servidor
* [Angular.js]() - FrontEnd

## Autores


## La Base de datos se crea automaticamente en caso contrario ejecutar crearla con los archivos adjuntos


* **Autor** - *Trabajo Inicial* - [AlfredZ12](https://github.com/AlfredZ12)

# Vistas
## Vista Administrador

  ![Alt text](./server/screens/login.png)
  ![Alt text](./server/screens/registroalumno.png)

  ![Alt text](./server/screens/registrodocente.png)

  ![Alt text](./server/screens/registroadmin.png)
  ![Alt text](./server/screens/registrogrupo.png)
  ![Alt text](./server/screens/registrocurso.png)
## Vista Alumno

  ![Alt text](./server/screens/alumno.png)
 
