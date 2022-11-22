# SERVER WEB - INSERT NEW INDEX.HTML
### 1.Creamos una nueva instancia, donde insertaremos el codigo para correr un servidor
![7](https://user-images.githubusercontent.com/83800315/203216241-e3372788-a223-46ae-884b-506933d94d7a.png)
### 2.Luego creamos un archivo HTML. Ingresamos el codigo "vi nombreArchivo.html"
![8](https://user-images.githubusercontent.com/83800315/203216473-9f6716b6-4ca1-41b9-af7a-de711884485e.png)
### 3.En la terminal, escribimos el codigo o el texto a visualizarse en el archivo. Para salir y guardar, teclamos "ESC" y escrbimos ":wq" y ENTER
![9](https://user-images.githubusercontent.com/83800315/203216582-8c1a3580-db35-4ca4-a3c2-346812141b91.png)
### 4.Ahora, debe insertar el archivo con el siguiente comando
#### docker cp nombreArchivo.html nombreServer:/usr/share/nginx/html/nombreArchivo.html
![10](https://user-images.githubusercontent.com/83800315/203216715-dd9ac2fd-79e7-4690-9219-6e861f0335ab.png)
### 5.Abrimos el server ingresando el número del puerto
![11](https://user-images.githubusercontent.com/83800315/203216828-da2a1e0c-4d78-4628-b5e0-261764cd9ade.png)
### 6.Al abrirse una nueva ventana, agregamos en la URL "/nombreArchivo.html" que finalmente se nos abrirá el documento creado con la información ingresada
![12](https://user-images.githubusercontent.com/83800315/203216999-4d927961-2f07-4f92-a488-5214c26b5429.png)
