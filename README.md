Patterns
========

// The following is a factory pattern that creates a "Student" object


function createStudent(name, class, age){

var obj = new Object();

obj.name = name;

obj.class = class;

obj.age = age;

alert("A new student is " + this.name+ "and te student is a " + this.class + "and is "+this.age+ "years old.")

return object;


}

Singleton Pattern
=========

// So what I was going for with this is it takes the createStudent function above and creates a gender for it.

var singleton (function(createStudent){
 
 var gender = (Math.random* 1)
 
 this.gender(0)
 
  return girl
 
 this.gender(1)
  
  return boy
 
 )
}
