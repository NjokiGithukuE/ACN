Create a class called Person which defines the generic data and functionality of a human.

A class is a collection of attributes and functions. Different languages use different terminology for these things, but the basic concepts are the same.

Your Person class should have the following attributes:

name
age
gender
interests. This is a list or array of strings.
Give your Person class a hello function:

Example usage:

// JavaScript:

let person = new Person('Ryan', 30, 'male', ['being a hardarse', 'agile', 'SSD hard drives'])
let greeting = person.hello()
console.log(greeting)