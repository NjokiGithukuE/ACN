n this challenge, you will create 3 classes.

Super class called Animal
Dog and Cat class both extend Animal class (a dog is an animal, and a cat is an animal).
Dog and Cat class should only have one function, which is their own implementation of the sound() function. This is polymorphism.
A Home class, lots of people have dogs and cats in their homes. Home should have a function called adoptPet that takes any Animal as an input and returns the number of pets that have been adopted thus far. The new pet should be stored in the Home object in an array/list. The Home object should also have a function called makeAllSounds.

let dog1 = new Dog();
let dog2 = new Dog("Simba")

dog1.eat();    // returns 'Rax eats'
dog1.sound(); // returns 'Bark'

dog2.eat()    // returns 'Simba eats'
dog2.sound() // returns 'Bark'

let cat1 = new Cat();
let cat2 = new Cat("Smokey")

cat1.eat();    // returns 'Stormy eats'
cat1.sound(); // returns 'Meow'

cat2.eat()    // returns 'Smokey eats'
cat2.sound() // returns 'Meow'


let home = new Home();
let dog1 = new Dog();
let dog2 = new Dog();
let cat = new Cat();


home.makeAllSounds();// this doesn't return anything
home.adoptPet(dog1); // 1
home.makeAllSounds();
// this returns:
// Bark

home.adoptPet(cat); // 2
home.makeAllSounds();
// this returns:
// Bark
// Meow

home.adoptPet(dog2); // 3
home.makeAllSounds();
// this returns:
// Bark
// Meow
// Bark