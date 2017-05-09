###### Shauna Walker
1. What are some advantages to using Javascript's built in iterator methods over writing you're own for loops?

There are many advatanges to using Javascript's built in iterator method over writing for loops. One is that is much cleaner. In the while loop and even for loop it is easy to forget the counter or comparison object. In this new ieterator there is no counter or comparison object.

2. What is the difference between map and forEach?

Both methods use looping but the map method is more condensed while thr forEach suffers from DRY- don't repeat yourself

3. What data type will filter return?

Filtering returns data as an array method

4. What's a simple use case for reduce?

A simple use case for reduce is adding up an array of numbers

5. Suppose Javascript had no map method, how would you write it?

If javascript had no map method it'd be written as function reduce(array) { let container = []; for (let item of array) { container.push(item); } return container; }

6. What is a Javascript prototype?

A Javascript prototype is an object that inherits methods and properties from its parent

7. What is a prototype chain? What is an example?

A prototype chain is the series of parent and child relationships between prototypes. 
```
var proto = {
    describe: function () {
        return 'name: '+this.name;
    }
};
var obj = {
    [[Prototype]]: proto,
    name: 'obj'
};
```

8. What is the Javascript data type that has no prototype?

The javascript data type that has no prototype is null.

9. How does Object.create() affect the prototype chain?

Object.create() affects the prototype chain because it adds another relationship to the protype chain by creating a new object based on the arguments

10. How do you check to see if an object has a property defined on itself rather than somewhere up the protoype chain?

You would check to see if an object has a defined property on itself by is .hasOwnProperty(). It returns true if the object has a unique property attached and flase if otherwise