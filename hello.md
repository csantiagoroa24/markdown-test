<!-- headings-->


# my title
## my tittle h2
### my tittle h3
#### my tittle h4
##### my tittle h5
###### my tittle h6 


<!-- formato-->
this is an *italican* text

this is an **strong** text

este es un ~~tachado~~

<!-- listas-->
* manzana
    * Manzana dos
* naranja
    * naranja dos
* tuti

1. uno
2. dos
3. tres

<!-- enlaces-->

[google.com](https://www.google.com)

[google.com](https://www.google.com "Custom title")

<!-- citas-->
> esta es una cita

---
___

<!-- alt 96 simbolo para codigo-->

`console.log('hola mundo')`

```javascript
const mongoose = requere('mongoose');

mongoose.set('useFindAndModify', false);
mongoose.connect('mongods://localhost/node-notes-db', {
    useCreateIndex: true,
    useNewUrlParser: true

})
    .then(db => console.log('DB is connected'))
    .catch(err => console.error(err));

```

```Java
    system.out.println("Prueba");

```

```html
<h1>Hola</h1>

```

<!--Tablas -->
|Tables       |Are          |Cool |
|-------------|:-----------:|-----|
|col 3 is     |rigth-aligned|$1600|
|col 2 is     |centered     |  $12|
|zebra stripes|are neat     |   $1|


<!-- IMG  --->

![Ejemplo de img url](https://www.tooltyp.com/wp-content/uploads/2014/10/1900x920-8-beneficios-de-usar-imagenes-en-nuestros-sitios-web.jpg)

![Ejemplo de img url](img1.jpg "peporrio")

<!-- GITHUB MARKDOWN--->

* [x] Task 1
* [] Task 2
* [] Task 3
* [x] Task 4