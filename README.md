.php
must be written in a file with .php extension

<?php  ?>
opening and closing tag
shouldnt leave empty space after closing tag
technically dont need a closing tag if 
there will be no more HTML code after it

echo print
both output things to the page.

//   #
both do single line comments

/*   */
multiline comment

single quotes and double quotes behave differently

single quotes ignore escape characters
single quotes will not use variables and display
any content inside them, "as is"

.
string concatination is done with a dot between 
them rather than plus sign like in JS

use upper-case for all constants

++
incrementing by one.
place ++ before variable to change value
immediately
or 
place after to use original value then increment


	$num = 5;
	$refToNum = &$num;
	$num = 40;
	echo '$refToNum = " . $refToNum;
THIS will display the variable name 
then a value.
the value displayed will be 40 because the & sign
there points to $num and although $num's value 
was changed after the declaration, it will still
show the new value.


.= 
to add on to an existing variable, you use .= 

=&
these operators together create an alias for 
an existing variable

${   }
to parse a variable, put it in between a set of
curly braces following a dollar sign

define()
to create a constant, use the define() function.
constants are automatically a global value
define("greeting", "Hello ${name}");
echo greeting;

you can also create an array constant
define("shoppinglist", ["milk","eggs","butter"];
echo shoppinglist[1];

arythmatic operators are the same as every other
language. including shorthand.


!= <>
not equal operators

== 
equal

!==
not identical

===
identical

<=>
spaceship
returns -1, 0, or 1 when one variable is less than
equal to or larger than another.

increment and decrement operators can be placed 
before or after the variable.
putting before the variable will increment or 
decrement before the value is returned 
placing after the variable will return the value 
then increment or decrement

&& and 
if both things are true.
but the word and behaves a little differently
than ampersands

or ||
if either thing is true

xor 
if one case is true but not the other

!
not

.
concatenation

.= 
concatenation assignment.
add on to an existing valaue

?:
//if empty($user) = TRUE, set $status = "anonymous"
echo $status = 
(empty($user)) ? "anonymous":"logged in";
//so basically:
// if something = true/false ? 
then option1 : option2;

??
if null
// variable $color is "red" if
// $color does not exist or is null
   echo $color = $color ?? "red";
 
if, else, elseif
all the same as in JS except elseif is
spelled as one word 

