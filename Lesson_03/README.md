# js-tutorial Lesson 3 Functions and Objects

## Functions

### Definition
A certin block of code that can be reused over and over again

### Parts
   
* Prototype: A function prototype is a definition that is used to perform type checking on function calls e.g `function doSomething(param1, param2, ...)`

* body: What will the function do

``` js
function doStuff(parametter){
    // code goes here.
}
```

> function reference *<u>name</u>* should follow same rules of variables see [lesson 1](https://github.com/icon-ramico/js-tutorial/tree/main/Lesson_01)

> A function can either be instructional or calculating **returning a value**.

Think of return as *Cartesian level*

when ever we ask for **X** = value we know what correspons the **Y** axis

## Objects

An object is a standalone entity, with properties{atributes} and values{state} pairs and a set of behaviors{methods}.

### Delaring

either lierary using syntax `{prop:value}` or using constructor `function Person(name){this.name=name}`

> properties *attrivbtes*  are accessed by either *Dot notation* o r*Square brackets property access: object['property']* 

The property can be a function *behavior* uses `this` keyword to refer itself.
