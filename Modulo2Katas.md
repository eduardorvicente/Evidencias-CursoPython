## Crear un entorno virtual

Crea un entorno virtual mediante ``venv``

![1](https://user-images.githubusercontent.com/83978334/153288699-9b80b0f9-1c8d-4a5f-bdfb-bfbdf8fc8d28.png)

Se crea en el directorio una carpeta con nombre env

![2](https://user-images.githubusercontent.com/83978334/153288817-1a517e58-6f9c-4b08-94f8-a23b75bb4544.png)
 
Para iniciar el entorno virutal ejecutamos el comando ``env\Scripts\activate``
 
![3](https://user-images.githubusercontent.com/83978334/153293818-af3ef1c5-7648-45fd-aba2-dea09808d328.png)


## Instalar una biblioteca

Se ejecuta el comando ``pip freeze`` para ver las bibliotecas instaladas en tu entorno:

```
pip freeze
```

![4](https://user-images.githubusercontent.com/83978334/153293846-5940cea0-bc56-4692-ab1d-d9318bffd67c.png)

    
 Al ejecutarlo no se obtiene respuesta ya que aun no hay nada instalado


Ejecuta el comando ``pip install`` para instalar una biblioteca:

 ```
 pip install python-dateutil

 ```
   
 ![5](https://user-images.githubusercontent.com/83978334/153294092-1dcc4eaf-c661-4d5f-ace9-3060104f1c77.png)


 
Al ejecutar nuevamente ``pip freeze`` para ver cómo ha cambiado la lista de bibliotecas, ahora se ve la siguiente lista:

```
python-dateutil==2.8.2
six==1.16.0
```
     
![6](https://user-images.githubusercontent.com/83978334/153294131-a0b4e694-219d-45ef-80fc-6015a273fb8d.png)

## Desactivar un entorno virtual

Tal vez necesites cambiar entre proyectos de python. Para hacer eso, debes salir (desactivar) tu entorno virtual.

Ejecuta el comando ``deactivate``:
```
deactivate
```
![7](https://user-images.githubusercontent.com/83978334/153294167-9f068c1a-527f-4bde-9bce-968e84b9cb80.png)

Al hacerlo cambia el mensaje de tu terminal ``(env)`` a cómo se veía antes.
