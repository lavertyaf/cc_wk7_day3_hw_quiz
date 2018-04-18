# cc_wk7_day3_hw_quiz

Polymorphism
What does the word 'polymorphism' mean?
Poly means many and morphic means change, so it allows objects to behave as if they are more than one thing.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Objects can behave as if they are a superclass object, as well as themselves.  They can use the methods attached to each object class.
If you have a computer super class, and subclasses of laptop and desktop, then polymorphism allows the laptop to behave as if it was a laptop, and also behave as if it was a superclass computer.

What can we use to implement polymorphism in Java?
We can use abstract classes and interfaces to implement PM.

How many 'forms' can an object take when using polymorphism?
Multiple forms (as opposted to inheriting from just one class).

Give an example of when you could use polymorphism.
If you want to have a an arraylist of different object types, this would not normally be possible since an arraylist can usually only contain one type of thing.  PM allows you to have a mixed arraylist.


Composition
What do we mean by 'composition' in reference to object-oriented programming?
Composition is when objects are composed of other objects.

When would you use composition? Provide a simple example in Java.
You would use composition when relating various class objects. A hotel is made up of other room objects eg. a bedroom, a conference room etc.

What is/are the advantage(s) of using composition?
Composition prevents the dead end risk that inheritance can lead to. Using interfaces in composition can allow programmes to be expanded and become future proof. Dependency inversion ensures that small details do not interfere with the higher policy, by providing an interface to become a bridge between high level and low level classes.

What happens to the behaviours when the object composed of them is destroyed?
If they live within the object they would also be destroyed, however if they live wihin the interface then they live on nd can be reused elsewhere.
