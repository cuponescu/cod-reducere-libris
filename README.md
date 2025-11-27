# Cod Reducere Libris

O colecție de coduri de reducere Libris. Le folosim pentru testarea cuvintelor cheie cod reducere Libris, voucher Libris, cupon Libris, și cod promotional Libris de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-libris` prin NPM:

```bash
npm install cod-reducere-libris
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-libris')

console.log(codes)

// [
//   {
//     site: 'https://www.libris.ro',
//     cod_reducere: 'LIBRIS10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la cărți'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-libris a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://www.cuponescu.ro

