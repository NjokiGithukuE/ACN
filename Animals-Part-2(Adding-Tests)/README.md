Your directory structure should look like this:

    >node_modules    <---- make sure this is in your .gitignore
    >spec
        > support
            - jasmine.json
        - animals_spec.js
    >src
        - animals.js
    - package.json


1. Add tests to your project.
2. The Dog and Cat class methods should still remain as per part 1 of the project.
3. Make sure the makeAllSounds()/make_all_sounds() method still works properly.
4. See the pseudocode examples below for what kinds of things should be tested.

Use Jasmine to test your code.

Then create tests for your eat() and sound() methods on the Dog and Cat classes with Jasmine.



//Dog Tests
let dog = new Dog();
Test -> Does <dog name> eats should Pass
Test -> Does dog Bark should Pass
Test -> Does dog Meow should Fail

//Cat Tests
let cat = new Cat();
Test -> Does <cat name> eats should Pass
Test -> Does cat Meow should Pass
Test -> Does cat Bark should Fail