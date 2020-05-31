# JS Cookies

## Installation
npm
```
npm install js-cookie-jar
```
yarn
```
yarn add js-cookie-jar
```

## Sample Usage

```javascript
import Cookie from 'js-cookie-jar'

// Creaye a cookie
// Cookie.create(name, value, days)
Cookie.create('mycookie', 123, 60)

// Reading a cookie
Cookie.read('mycookie')
// Result: 123

// Deleting a cookie
Cookie.remove('mycookie')
```