# Propuesta TP DSW

## Grupo
### Integrantes
* 42895 - Gagliano, Daniel
* 39233 - Rohr, Claudio

### Repositorios
* [frontend app]-
* [backend app][(https://github.com/daniel-gagliano/TP-DSW-CINE)]


## Tema
### Descripción
La plataforma ofrece una experiencia al usuario permitiéndole explorar la cartelera, seleccionar sus películas preferidas, elegir los asientos y completar la compra en línea. Para los administradores proporciona las herramientas para gestionar el inventario de entradas y programar los horarios de proyección.

### Modelo
Diagrama de Entidad-Relacion <BR/>

(https://drive.google.com/file/d/1lukkYYM_x9WASzTJszFzP0C0eT_pA_6D/view?usp=drive_link)

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Sucursal<br>2. CRUD Cliente<br>3. CRUD Tipo Pelicula|
|CRUD dependiente|1. CRUD Pelicula {depende de} CRUD Tipo Pelicula<br>2. CRUD Sala {depende de} CRUD Asientos|
|Listado<br>+<br>detalle| 1. Listado de peliculas filtrado por nombre y genero => muestra datos completos de la pelicula, tipo de pelicula y listado de salas con sus horarios<br> 2. Listado de sucursales filtrado por nombre y localidad, muestra datos completos de la sucursal
|CUU/Epic|1. Reservar una entrada para una pelicula y sala<br>


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Pelicula<br>2. CRUD Pelicula<br>3. CRUD Sucursal<br>4. CRUD Cine<br>5. CRUD Sala<br>6. CRUD Asiento<br>7. CRUD Cliente|
|CUU/Epic|1. Realizar la reserva de una entrada<br>2. Realizar facturacion de la entrada|

