# Incorrect Use of 'Img Attribute in Ada

This example demonstrates a common mistake made by Ada beginners when using the `'Img` attribute with arrays.  The `'Img` attribute is used to get a string representation of a type, but it needs to be applied to the correct type.  If directly used on an array element of an integer type, it'll result in compilation error, not a runtime error. 

The solution shows the correct way to get the string representation of an Integer array element.