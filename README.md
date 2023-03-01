# Código y documentación M04-UF1
Cyberseguridad: Llenguatge de Marques (M04-UF1)

## XML
Aquí irán los apuntes de **XML**

XML, o Lenguaje de Marcado Extensible, es un formato de archivo que se utiliza para almacenar y transportar datos en un formato legible por humanos y por máquinas. Las etiquetas son uno de los componentes más importantes de XML y se utilizan para definir la estructura y el contenido de los datos.
### Etiquetas Pares
**Las etiquetas en XML siempre deben ser pares**, lo que significa que hay una etiqueta de apertura y una etiqueta de cierre. La etiqueta de apertura comienza con el símbolo "<" seguido del nombre de la etiqueta, y la etiqueta de cierre comienza con el símbolo "</" seguido del mismo nombre de etiqueta. Por ejemplo:
>
>**\<nombre>Juan\</nombre>**
>> En este ejemplo, "nombre" es el nombre de la etiqueta, "Juan" es el contenido de la etiqueta y la etiqueta completa es una etiqueta pareja, ya que hay una etiqueta de apertura "<nombre>" y una etiqueta de cierre "</nombre>".
### Etiquetas Impares
>
> También hay ***etiquetas inpares***, que sólo tienen una etiqueta de apertura y no tienen una etiqueta de cierre correspondiente. Estas etiquetas se utilizan para indicar que un elemento no tiene contenido. La etiqueta de apertura para una etiqueta inpares se ve así:
>
>>**\<elemento/>**
#Ejemplo de COdigo de XML
```XML
<?xml version="1.0" encoding="UTF-8" ?>

<characters>
 
	<character id_character="1">
		<name>Eustaquio</name>
		<surname>Mendoza</surname>
		<age years="197" />
		<race>Enano</race>
		<class>Artificiero</class>
		<gender abbrev="">Non-Binary</gender>
		<height cm="130" />
		<weight kg="80" />
		<language abbrev="prt">Portugues</language>
	</character>
 
	<character id_character="2">
		<name>Mariana</name>
		<surname>Rajoya</surname>
		<age years="1200" />
		<race>Hada</race>
		<class>Tanque</class>
		<gender abbrev="F">Female</gender>
		<height cm="25" />
		<weight kg="3.5" />
		<language abbrev="ROU">Rumano</language>
	</character>
 
	<character id_character="3">
		<name>Mortadelo</name>
		<surname>Filemon</surname>
		<age years="20" />
		<race>Centauro</race>
		<class>Arquero</class>
		<gender abbrev="M">Male</gender>
		<height cm="3.5" />
		<weight kg="200" />
		<language abbrev="ELL">Elingles</language>
	</character>
	
	<character id_character="4">
		<name>Messi</name>
		<surname>Leo</surname>
		<age years="50" />
		<race>Gigante</race>
		<class>Healer</class>
		<gender abbrev="N">Non-Binary</gender>
		<height cm="1.6" />
		<weight kg="100" />
		<language abbrev="EUK">Euskera</language>
	</character>
	
 </characters>
 ```

## DTD
Los _apuntes de_ DTD

> Un gran poder conlleva 
>
> Una gran p...
>
> -Descartes 2004
>
> Esto es una cita
>> **Y esto una cita dentro de una cita**
> Seguimos

---
# MARKDOWN

Un enlace a la mejor web del mundo:

[CondorChem](https://condorchem.com)
y este [enlace](https://enti.cat) es otro enlace.

## Imagen incrustada
### EPICO

![Meme Maligno](https://i.kym-cdn.com/entries/icons/original/000/039/761/nerdfacecover.jpg)
			![Prova GIF](https://media.tenor.com/d914QufzT_QAAAAC/cat-epico-meme.gif)

### Ejemplo de resaltado de sintaxis

```kotlin
fun main(args: Array<String>) {

	print("Hola Guapa")
	}
```
### Lista de Tareas

- [ ] Primera Tarea
- [x] Segunda Tarea
- [ ] Tercera Tarea


### Carácteres extendidos

:point_right: :flushed: :point_left:

### Estilo de carácteres

*cursiva* _cursiva_

**negrita** _negrita_

~~TACHADO~~

~~***tachado negrita y cursiva***~~

### Tablas

| id_character | name | age| level |
| --- | --- | --- | --- |
| 1 | Esutaquio | 197 | 99 |
| 2 | Mariana | 20 | 100 |
| 3 | Mortadelo | 100 | 1 |
| 4 | Messi | 44 | 32 |
