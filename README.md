# Lab_3B_Fan_Class

For this problem, you will be creating a class and using the Main class to test your output.  Leave the Main class alone for now and create your class in the Fan file.

Design the class to represent a fan.  The class should contain the following:
- An `int` data field named `speed` that specifies the speed of the fan (the default is 1).
- A `boolean` data field named `on` that specifies whether the fan is on (the default is false).
- A `double` data field named `radius` that specifies the radius of the fan (the default is 5).
- A `String` data field named `color` that specifies the color of the fan (the default is blue).

- A default constructor that creates a default fan using the values above.  This should be the only constructor.  Do **not** include a constructor that has any parameters.
- The accessor and mutator methods for all four data fields.
- A `toString()` method that returns a String description for the fan.  If the fan is on, the method returns the fan speed (print slow if the speed is 1, medium if it is 2, and fast for all other values), color, and radius printed and labeled nicely.  If the fan is not on, the method returns the fan color and radius along with the string “fan is off” printed nicely.

Complete the Main class as following to test your Fan class:
- Create two Fan objects.
- Use the setters to have the first fan object have a speed of 3, radius 10, color yellow, and be on.
- Use the setters to have the second fan object have a speed of 2, radius 5, color blue, and be off.
- Display the objects by invoking the toString method.
