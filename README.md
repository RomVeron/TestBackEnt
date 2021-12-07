# TestBackEnt

Se realizo el test con la herramienta de:
 Visual Studio 2022
 .NET 5
 SQLServer


Se creo la arquitectura del test en capas y se utiliza el patrón Repository 
se agregaron persistencias utilizando EntityFramework y JWT con Identity para la seguridad y autenticacion de la API
Se puede realizar las consultas desde el navegador con Swagger o utilizar postman o Insomnia
Se utilizo un generador de cadenas web para para utilizar un tocken de 32digitos

Las migraciones se realizaron desde la terminal:
Con le comando Add-Migration y Update-Database

Se debe primero crear un usuario, luego realizar el login 
Copiar el la cadena Token y Pegarlo en el Token Bearer del postman o insomnia
Para realizar las consultas
