# Hoja de ruta del curo JavaScript

## Inicial

#### Es la seccion inicial del curso en Youtube

# Array

```
const arr = ['Pera', 'Manzana', 'Uva', 'Kiwi', 'Anana', 'Cereza','Pomelo', 'Limon']
```
```
//Prop elimina el ultimo elemento del array
arr.pop()
```
```
console.log(arr)
//Salida => [ 'Pera',   'Manzana', 'Uva',    'Kiwi', 'Anana',  'Cereza', 'Pomelo']
```
```
//agrega un elemento al final del array
arr.push('Pera')
console.log(arr)
//Salida => [ 'Pera',   'Manzana', 'Uva',    'Kiwi', 'Anana',  'Cereza', 'Pomelo', 'Pera']
```
```
//convertir en un strin a nuestro array
const cadenaTexto = arr.toString();
console.log(cadenaTexto)
//Salida => Pera,Manzana,Uva,Kiwi,Anana,Cereza,Pomelo,Pera
```
```
//no tiene devolucion
arr.forEach(elemento =>{
    console.log(elemento)
})
```
```
// shift => Transforma el array original quitando el primer elemento y enviandolo a otra variable
const arrPrimerElemento = arr.shift()
// arrPrimerElemento => ['Pera']
//arr => [ 'Manzana', 'Uva',    'Kiwi', 'Anana',  'Cereza', 'Pomelo', 'Pera']
console.log(arrPrimerElemento)
console.log(arr)
```
```
//filter, devuelve todos los elementos que coincidan con la condicion dada por el callback
const arrFilter = arr.filter(arr => { 
    if(arr == 'Uva' || arr== 'Kiwi'){
        return arr
    }
 })
 console.log(arr) //El array sin ser modificado
 console.log(arrFilter) // solo los que coincidieron con el filtro
```
```
 const arrSize = arr.unshift('Tomate', 'Zapallo')
 console.log(arrSize) //la cantidad de elementos
 console.log(arr) //el nuevo array
```
