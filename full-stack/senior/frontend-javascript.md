Below are senior level frontend javascript developer Q&As.

-------------------------

### 1. ES6 functional javascript code

*Below is an array of people and their pets, along with an array of pet IDs. Write some code that takes two inputs: `people` and `petIds` and returns the original `people` array and for each matching pet id insert a property `{ species: 'cat' }` into matching pet object.*

*e.g.* `{ id: '2', name: 'Rolf', species: 'cat' }`

* Clean and expressive
* Follows solid principals
* Testable
* Should not mutate original value (immutability)
* Over engineer it... show off :-) 

```javascript
const petIds = ['2','3','5'];

const people = [
  {
    id: '1',
    name: 'Jill',
    sex: 'female',
    age: 32,
    pets: [
      { id: '1', name: 'Kitty'},
      { id: '2', name: 'Rolf'}
    ]
  },
  {
    id: '2',
    name: 'Sam',
    sex: 'male',
    age: 16,
    pets: [
      { id: '3', name: 'Pretty boy'}
    ]
  },
  {
    id: '4',
    name: 'Pete',
    sex: 'male',
    age: 33,
    pets: [
      { id: '4', name: 'Misty'},
      { id: '5', name: 'Milo'}
    ]
  },
  {
    id: '5',
    name: 'Jess',
    sex: 'female',
    age: 21,
    pets: []
  }  
]
```

```javascript
// paste your code here
```

-------------------------

### 2. Dependencies

*Define NPM, Yarn and the difference between the two.*

-------------------------

### 3. Variable scope

*What is the purpose of `let` keyword in javascript?*

-------------------------

### 4. Stateless components

*Explain the reasoning behind a stateless component along with a small code example. Use React or Vue.*

```javascript
// past your code here
```
