# JavaScript Quiz

I have compiled some basic JavaScript language questions so developers can test their knowledge, and also learn some nuances of the language from the detailed answers to each question.

### 1. What is the result of:

```javascript
('b'+'a'+ +'a'+'a').toLocaleLowerCase()
```

**a)** `SyntaxError`</br>
**b)** `'baaa'`</br>
**c)** `'banana'`</br>
**d)** `'baa'`</br>

### 2. What is the result of:

```javascript
let num = '10'

num += num++
```

**a)** `'1010'`</br>
**b)** `NaN`</br>
**c)** `'1011'`</br>
**d)** `21`</br>

### 3. What is the result of:

```javascript
(function () {
  var num1 = 10
  var num2 = 20

  return sum()

  function sum() {
    return num1 + num2
  }
})()
```

**a)** `undefined`</br>
**b)** `NaN`</br>
**c)** `30`</br>
**d)** `ReferenceError`</br>

### 4. What will be the output value of log 1 and log 2?

```javascript
function Person (firstName, lastName) {
  this.firstName = firstName
  this.lastName = lastName
}

let person = Person('Guilherme', 'Moura')

console.log('log 1: ', person)
console.log('log 2: ', firstName, lastName)
```

**a)** `log 1: Guilherme Moura | ReferenceError`</br>
**b)** `log 1: undefined | log 2: Guilherme Moura`</br>
**c)** `log 1: { firstName: 'Guilherme', lastName: 'Moura'  } | log 2: Guilherme Moura`</br>
**d)** `log 1: { firstName: 'Guilherme', lastName: 'Moura'  } | ReferenceError`</br>

### 5. What is the result of:

```javascript
(3,5 - 3) * 2
```

**a)** `0.999999`</br>
**b)** `0,5`</br>
**c)** `1`</br>
**d)** `4`</br>

## Check out the answers:

- <a href="https://github.com/mouraggui/js-quiz/blob/master/answers/pt-br.md" target="_blank">pt-BR</a>
- <a href="https://github.com/mouraggui/js-quiz/blob/master/answers/en-us.md" target="_blank">en-US</a>