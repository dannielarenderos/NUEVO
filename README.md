# Título H1
### Subtítulo h3


Citas 

>  Un país, una civilización se puede juzgar por la forma en que trata a sus animales. 
>  —Mahatma Gandhi


Ejemplo de lista desordenada

- Elemento 1
* Elemento 2
+ Elemento 3

Ejemplo de lista desordenada anidada 

- Elemento 1
* Elemento 2
    + Elemento 3
    + Elemento 4
        * Elemento 5
    + Elemento 6
+ Elemento 7
    
    
    
    
Ejemplo de lista ordenada

1. Elemento 1
2. Elemento 2
3. Elemento 3

Ejemplo de lista ordenada anidada 

1. Elemento 1
2. Elemento 2
    * Elemento 3
    * Elemento 4
        * Elemento 5
    + Elemento 6
+ Elemento 7
    

Ejemplo códigos de bloque 

~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras. 

~~~


```python
# Se concatena el nombre de departamento y municipio para el df de homicidios
dept_mun_df = []
for depto, mun in zip(df['Departamento'], df['Municipio']):
  df_concat = depto+','+mun
  dept_mun_df.append(df_concat)

#Agrega la columna concatenada
dm_df_series = pd.Series(dept_mun_df)
df['dept_mun_str'] = dm_df_series.values
```


Ejemplo de líneas separadoras

***
---

Ejemplos de énfasis

*cursiva*
_cursiva_
**negrita**
__negrita__

***cursiva y negrita***	
___cursiva y negrita___

---

Ejemplo de links

*Se crean escribiendo la palabra o texto enlazada entre [] corchetes, y el link en cuestión entre () paréntesis.*

[enlace en línea](https://github.com/)	

Ejemplo de enlaces como referencia

*[nombre que quieres darle a tu enlace][nombre de tu referencia]
[nombre de tu referencia]: http:www.tuenlace.com*

--- 

Ejemplo de imágenes

*![Texto alternativo](ruta imagen)*

![Texto alternativo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)


