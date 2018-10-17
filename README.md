# Datatypes:= A datatypes is a format of information that behaves in a specific way.

Six primitive  data types:
* Boolean := True and false 
* Number:= Any number integer or floating
* String:= any text
* Undefined:= A space in memory that has nothing
* Null:= A space in memory that has been set to empty

# Number
// integer numbers
-3;
-1;
0;
1;
// floating-point (i.e. decimal) numbers
-42.42;
-2.718;
-0.25;
.897
3.14;
199.99;

# NaN=(Not a Number)
NaN must be uppercase otherwise JavaScript will throw an error.


* Variables
* Variable names in JavaScript can't contain spaces.
Variable names also can't start with numbers.
Variables can also store the result of any expression.
that mean 
var x=2+2

# Question
What does the following evaluate to?

10 % 5
ans=0
i mean  remainder is 0



# Remember
Logical operators
true && true;   // true
true && false;  // false
false && true;  // false
false && false; // false

true || true;   // true
true || false;  // true
false || true;  // true
false || false; // false

!true;          // false
!false;         // true

# Question
What will the following evaluate to?

true && (false && true)
ans false

What does this evaluate to?

(21 * 2) > (22 * 1)
(42)>(22)
ans true

#What will the following evaluate to?

"hello" == "Hello";

false
(because one string contains an uppercase letter they are not identical.)

#
What will the following evaluate to?

100 * 5 === "500"

ans=false(because one side using string)

#bNotes

You can always check something's type in JavaScript using the typeof operator.


# There are only six "falsy" values in JavaScript.
false
null
undefined
0
''
NaN
