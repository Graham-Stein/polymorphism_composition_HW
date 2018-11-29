Polymorphism & Composition Homework - Quiz
Polymorphism

What does the word 'polymorphism' mean?
Having the ability to change into many different forms.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A sub-class of athlete is runner. The runner can be treated as being an athlete or a
runner. Or two classes that implement IBuy (that has a buy method) can be treated as
themselves or an instance of IBuy.

What can we use to implement polymorphism in Java?
Interfaces or super/sub classes.

How many 'forms' can an object take when using polymorphism?
Infinite, but only one at a time.

Give an example of when you could use polymorphism.
Two classes that implement IBuy (that has a buy method) can be treated as
themselves or an instance of IBuy.

Composition
What do we mean by 'composition' in reference to object-oriented programming?
Composing the attributes and behaviours of a class using other class objects as
attributes or implementing Interfaces to add behaviours.

When would you use composition? Provide a simple example in Java.
Making a car class from class components such as engine, fuel tank etc.

What is/are the advantage(s) of using composition?
This modular approach is more flexible and reusable.

What happens to the behaviours when the object composed of them is destroyed?
Within the class these are lost, but where the behaviours are encapsulated in
Interfaces or other classes these are still available to be re-used.
