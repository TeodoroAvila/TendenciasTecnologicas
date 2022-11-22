# Pratica postgresql y pgadmin con docker compose
## Informe contenedores de postgresql y pgadmin a partir de archivos de configuración YML.
### 1.Creamos una caperta en donde se encontrara nuestro archivo YML y accedemos a nuestra carpeta que acabamos de crear utilizamos el comando cd.
![1](https://user-images.githubusercontent.com/83800315/203196614-c0e55669-7991-4e0f-a27a-6782ffdeda18.PNG)
### 2.Una vez dentro de la carpeta, vamos a crear el archivo en el cual encontraremso nuestros contenedores, para ello ocupamos el comando vi.
![2](https://user-images.githubusercontent.com/83800315/203196867-633becab-0d08-4560-96db-150b0d7b18ab.PNG)
### 3.Una vez creado nuestro archivo vamos a editarlo para crear el contenedor de postgres y pgadmin nos quedaria asi.
![3](https://user-images.githubusercontent.com/83800315/203197004-4804a97d-baa3-410e-8e4d-d9ffa41bf481.PNG)
### 4.Una vez configurado guardamos con el comando :w y salimos con el comando :q!. Con el comando cat verificamos que el archivo se haya guardado bien y colocamos el comando docker-compose up -d para que se creen los contenedores.
![4](https://user-images.githubusercontent.com/83800315/203197152-7d148a6d-2187-4f57-8bd9-ef97e86092d3.PNG)
### 5.Comprobamos que se haya creado, abrimos el puerto 8090 y colocamos el usuario y contraseña que asignamos.
![6](https://user-images.githubusercontent.com/83800315/203197406-69cf65ae-6aa6-40f0-bfc2-eaf95f90bc96.PNG)
### 6.Procedemos a crear un nuevo servidor y configurasmos las conexion.
![7](https://user-images.githubusercontent.com/83800315/203198061-a14c99d4-0c99-4e89-b353-a66f3b8fc921.PNG)
### 7.Procedemos a crear la base de datos
![8](https://user-images.githubusercontent.com/83800315/203198252-a9d3759e-2bca-4076-8c32-b5ab58d1a04c.PNG)
### 8.Le ponemos un nombre y damos en guardar.
![9](https://user-images.githubusercontent.com/83800315/203198413-3cf33e1a-cf37-424b-85f7-4966acfde70c.PNG)
### 9.Listo tenemos creado nuestros contenedores junto a la base de datos.
![10](https://user-images.githubusercontent.com/83800315/203198502-7a583fb0-0286-42c3-8c63-839e1cbdf194.PNG)
