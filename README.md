#	MongoDB


##	Colecciones: 
Las colecciones en MongoDB son como tablas en una base de datos SQL, pero son grupos de documentos en lugar de grupos de registros, por ejemplo puedo tener una coleccion de datos (usuarios, productos, categorias, vendedores, etc.)<br>
**Ejemplo:**
*	Usuarios:<br>
	-	name: mike
	-	created: 18/02/23 
<br>Se guardan en un objeto JSON, por ejemplo:
```js
//  Campo: Valor
{
  name: "adrian",
  age: 26,
  status: "A",
  groups: [ "news", "sports" ]  
}
```
La coleccion(**documentos**) es un **objeto con sus propios datos** (name, age, status, groups, etc.) pero con valores diferentes.<br>




Comandos comunes:
*	**show dbs**: Muestra las bases de datos.
*	**db**: Muestra la base de datos actual.
*	**use NOMBRE_DB**: Usa una nueva base de datos - Pero es necesario agregar almenos 1 datos para que se cree la base de datos.
*	****: .
*	****: .




















#	Requisitos previos:
##	[Descargar](https://www.mongodb.com/try/download/community)
Consultar la version: `mongod -version` la versión actual es: 6.0.4

##	[Descargar MongoDB Shell Download](https://www.mongodb.com/try/download/shell)
La versión actual es: 1.7.1
Después de descomprimir el archivo: en la carpeta **bin** copiar el archivo `mongosh.exe` y pegarlo en la carpeta **bin** de MongoDB
