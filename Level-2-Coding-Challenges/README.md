Task 2.1
Update your existing square function so that it takes 2 parameters but do not overload the square function. The first parameter should be the size of the square and the second one should be the character to use when drawing the square. The second parameter should be optional.

For example, square(2) should output:

##
##
For example, square(2, '*') should output:

**
**
Task 2.2
Upgrade your triangle function so that it takes in an optional argument named mode but do not overload the triangle function.

triangle(3) should print:

#
##
###
triangle(3, "left") should print:

#
##
###
(in other words, the default mode is left)

triangle(3, "right") should print:

  #
 ##
###
triangle(3, "isosceles") should print:

  #
 ###
#####
Negative numbers should still print things upside down.

For example, triangle(-3, "isosceles") should print:

#####
 ###
  #
Up for a Challenge?
This section is not compulsory but if you do this, we’ll think you’re cool.

Add some functionality to triangle so that an error/exception gets raised if an incorrect mode is entered.

Task 2.3
Write a function that takes a list of strings and prints them as columns with a single space between them.

For example, columns(["Write","good","code","every","day"]) gets printed as:

W g c e d
r o o v a
i o d e y
t d e r
e     y