# Hacking Cinepolis

## El objetivo general 
`es analizar y obtener  información de la página de cinépolis con el fin de poder obtener la cartelera del día de hoy del complejo deseado`.

## Ejemplo

- bot: `porfavor indicame el complejo que deseas la cartelera:`
- input: `plaza cumbres`
- bot: 
```
Se, encontraron los siguientes complejos que coinciden con tu búsqueda: 
1) plaza cumbres x
2) plaza cumbres y
3) plaza cumbres z
cual deseas seleccionar (1,2,3)
```
- input: `1`
- bot: `la cartelera para el dia de hoy en 'plaza cumbres x' es: a, b, c, d. gracias por usar nodejs....`

## Puntos a contemplar
- `No hacer uso` de ciclos for, while, etc, o switches.
- `No hacer uso` de `var`, sólo usar `let` y `const`.
- En caso de Promesas (`Promise`) utilizarla con su sugar syntax `async y await`
- Analizar la página de cinepolis para encontrar el mejor medio de obtención de datos: ej Web Scraping o consumo REST con json o soap
- Cada interaccion con el bot se realiza una consulta a cinepolis para obtener la ultima información disponible a partir del método antes definido
- La estructura del proyecto debe estar en diversos archivos: ej `index.js`,  ||| `src/consultasCinepolis.js`, etc. La estructura será definida por ti y la respaldarás.
- No es necesario usar ningún tipo de procesador como babel, gulp, o similares. Sólo Javascript vanilla que te permita nodejs.
- definir el archivo `.gitignore`
- definir el archivo `package.json` por medio de yarn.
- usar Yarn, no usar npm
- hacer commits con mensajes claros (solo usar la terminal) 
- no subir cambios a la branch master, crear una nueva brancha llamada `revision/martin` que tenga todos tus cambios

## Librerías a utilizar:
- Cualquier librería aportada por NodeJs y su documentación
- Usar Axios para consumo HTTP (librería basada en promesas)


# **¡éxito!**

Y recuerda:
- come frutas y verduras.
- consume local
- toma agua
