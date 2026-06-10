# Analisis de Normalizacion - Ejercicio 31

## Tabla original

Describa la tabla sin normalizar del archivo `datos/datos-sin-normalizar.csv`.

``` text
En la tabla sin normalizar encontramos varios datos agrupdos dentro de un mismo espacio, como lo son los productos, precios, catidades.

``` 
### Tienda_Campus

| id_venta | cliente_nombre | cliente_email | productos_comprados | precios | cantidades | vendedor | sucursal |
| :---: | :--- | :--- | :--- | :---: | :---: | :--- | :--- |
| **1** | Ana Perez | ana@email.com | Mouse gamer, teclado RGB | 125 \| 260 | 1 \| 2 | Luis Rojas | Sede Norte |
| **2** | Carlos Diaz | carlos@email.com | Monitor 24, Mouse gamer | 1450 \| 125 | 1 \| 1 | Marta Lopez | Sede Centro |
| **3** | Ana Perez | ana@email.com | USB 64GB , Base Laptop | 75 \| 180 | 3 \| 1 | Luis Rojas | Sede Norte |

## Problemas detectados

- Grupos repetidos: **Productos_comprados, Precios, Cantidades.**
- Datos duplicados: **Mouse gamer, Ana Perez,Luis rojas, Sede Norte.**
- Dependencias parciales:
- Dependencias transitivas:
- Anomalias de insercion:
- Anomalias de actualizacion:
- Anomalias de eliminacion:

## Dependencias funcionales

Escriba las dependencias funcionales principales.

```text
A -> B
A, B -> C
```

## Primera Forma Normal (1FN)

Explique que cambios hizo para eliminar grupos repetidos y valores multiples.

## Segunda Forma Normal (2FN)

Explique que dependencias parciales elimino.

## Tercera Forma Normal (3FN)

Explique que dependencias transitivas elimino.

## Modelo final

Liste cada tabla final, su llave primaria y sus llaves foraneas.

| Tabla | Llave primaria | Llaves foraneas | Proposito |
| --- | --- | --- | --- |
|sd | d| d| d|

## Justificacion

Explique por que el modelo final reduce duplicidad y evita anomalias.
