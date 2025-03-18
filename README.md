# Javascript crash course

## Table of content

1. [Menampilkan sesuatu ke console](#menampilkan-sesuatu-ke-console)
1. [Variable](#variable)
1. [Tipe Data](#tipe-data)
1. [Operator](#operator)
1. [Conditionals](#conditionals)
1. [Loops](#loops)

-----------

### Menampilkan sesuatu ke console  

Kita dapat menampilkan sesuatu ke console menggunakan `console.log`
```js
console.log('hello world')
```

### Variable

Ada 3 cara utama membuat variable di JS yaitu `var`,`let`, dan `const`  
```js
var namaVariable = 'value'

let namaVariable1 = 'value1'

const namaVariable2 = 'value2'
```

### Tipe Data

String, Number, Boolean, Array, Object, dan sebagainya
```js
console.log(typeof 'sample string')
console.log(typeof 123)
console.log(typeof true)
console.log(typeof false)
```

### Operator

- `+`
- `-`
- `*`
- `**`
- `/`
- `%`
  
- `=`

- `==`
- `===`
- `!=`
- `!==`
- `<`
- `<=`
- `>`
- `>=`

- `++`
- `--`

### Conditionals

if Statement
```js
if (true) {
  // do something
} else if (false) {
  // do something
} else {
  // do something
}
```

switch Statement
```js
let value = 3

switch (value) {
  case 1:
    console.log(1)
  case 2:
    console.log(2)
  case 3:
    console.log(3)
  case 4:
    console.log(4)
    break
  case 5:
    console.log(5)
    break

  default:
    console.log('x')
    break
}
```

Exercise :
```js
let nama = 'James Lebron'
let umur = 21
let sukaDurian = false

console.log(`Nama saya ${nama}`)
console.log(`Saya berusia ${umur} tahun`)
console.log(`Saya sudah punya KTP`);
console.log(`Saya tidak suka durian`);
```


### Loops

Standart for loop
```js
for (let i = 0; i < 5; i++) {
  console.log('Saya berjanji tidak akan mencoret-coret tembok lagi')
}
```

