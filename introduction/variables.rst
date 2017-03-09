==================
Variables
==================

In programming, a variable provides us with named storage that our programs can manipulate. A variable's name can be the letter a, the word frog, or just nonsense, like dj6vEc1418. You can give a variable a value using the ``=`` sign::

    x = 3
    frog = True
    dj6vEc1418 = "Apple"


Notice that the value assigned to a variable can change. It can be a number,
a word, or even another variable.

Variables are probably the most used programming feature. They help keep track
of data, and are the essence of object-oriented programming, which is what FRC
uses.

In FRC, variables are usually assigned to things like motor controllers, sensors, servos, and joysticks.

Naming
------

Giving variables good names is an integral part of writing good code. You will most likely be working with other people on you code, and it is important that they can read and understand your code just as well as you can. By naming your variables clear, concise names, it makes reading code in the future 10x easier. For example::

  ts = 100
  topSpeed = 100

It is clear that the name ``topSpeed`` is a better variable name, because you can understand what the variable is. ``ts`` on the other hand isn't very understandable, and you'll have to look at other code to figure out what it means.

Variable Definitions
------

As stated before, a variable provides us with named storage that our programs can manipulate. Each variable in any object-orientated program has a **type**.
The type can determine the size and layout of the variable's memory, the range of values within the specified memory, and the set of operations that can be applied to the variable.
Many programmers refer to variables as "variables" or "objects" interchangeably.

 Here are some examples of some *type specific* variables:

  int sum = 30
  string alphabet = "abcdefghijklmnopqrstuvwxyz"
  double multipler = 3.48
  char c = 'P'

There are many different types of type specifics for variables, including the ones above. Each one is unique in their own way, therefore some cannot be interchangeable. For example, if you multiply an integer by a double, and the variable that is assigned for the multiplication is an integer, the answer will show know remainders even though one of the objects being multiplied is a double.

*Quick Definition:*
Object
    An object is a region of memory that can contain data and has a type
