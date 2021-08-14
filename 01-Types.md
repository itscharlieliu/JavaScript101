# Types

## Dynamic Typing
JavaScript is a loosely typed and dynamic language

## Goals
- Students will be able to differentiate between data types
- Student will be able to use both Structural types and primitive types

## Notes

 - Variables are not associated with any particular value type, and can be changed at any time.
- Currently has 9 different types
  - Primitive types
    - undefined
      - A variable that has not been assigned a value
    - null
      - An "empty" value
    - Boolean
      - True or false
    - Number
      - Numbers. This one is pretty self explanitory
      - 1, 2, -3, 1.5, Infinity, etc
    - String
      - A collection of characters
      - "Hello"
    - BigInt
      - Can be used to store numbers even bigger than Number can store
    - Symbol
      - An anonymous unique value
      - Not too important for now
    - Note the difference between _undefined_ and _null_

    - Practice
      - When do you think would be a good time to use each of these data types?
  - Structural types
    - Object
      - Any "constructed" object
      - Examples:
        - Array, Map, Set, Date, etc
      - Think of it like a "container" for real data (primitives)
    - Function
      - Code snippet that can be called
      - Javascript is weird because it is also technically an object
    - Practice
      - When would you use object instead of primitive data types?
  - Mutable vs Immutable
    - Mutable
      - Can be changed, without changing the variable address
      - Ex) Arrays, Objects, etc
    - Immutable
      - Opposite of mutable
      - Can only be changed if we create a new data structure 
        - Ex) Strings, Numbers, any other primitives
    - Mutable data structures tend to be used when writing object-oriented code, while Immutable data tends to be used when writing functional code
- Homework
  - Try to write a Javascript Program that can calculate the days left until christmas
  - You will be using the Date object, as well as the number data type
  - Date documentation: 
    - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date