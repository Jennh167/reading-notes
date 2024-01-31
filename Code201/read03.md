# Read 03 Assignment

__*Learn HTML*__
__Ordered and Unordered lists.__

1. __When should you use an `<unordered list>` in your HTML document?__
You should use an unordered list when the items in the list don't have specific ordering or ordering would be pointless.

2. __How do you change the `<bullet style>` of unordered list items?__
To change the bullet style, you'd change it in CCS by using the `<list-style-type>` property.

3. __When should you use an `<ordered list>` vs an `<unorder list>` in your HTML document?__ You should order a list if unordering it changes the meaning of the list. For example, a recipe list most likley would need to be ordered due to the order in which the list needs to be followed however a shopping list probably wouldn't need to be ordered.

4. __Describe two ways you can change the numbers on `<list items>` provided by an `<ordered list>`__ One way to change the numbers on list items in an ordered list is after the `<ol>`, use `type=i`. It changes the numbers to lowercase roman numerals. Another way is to use `type=A` to change the numbers to uppercase letters.

__*Learn CSS*__
__The Box Model.__

1. __Describe the CSS properties of `<margin>` and `<padding>` as characters in a story. What is their role in a story titled: “The Box Model”?__ There once was a gal named Paddington (Paddy for short) and a gentleman named Marginald (Margin for short). Margin loved Paddy and loved to protect and be with her. They both loved space and not just the space above them but all around them. Now Paddy had a father named Borden. Borden didn't like the thought of Paddy dating anyone, especialy Margin. Borden had heard that Margin sometimes would have more than one gal at a time and that made him very cautious for his daughter. So he did everything in his power to keep them apart. Sometimes to the point of squishing Margin into uncomfortable positions. But regardless of Margin's efforts, Borden was always right there. Nevertheless, Margin still never gave up and follows her everywhere she goes even until this very day!

2. __List and describe the four parts of an HTML elements box as referred to by the `<box model>`.__ There are four parts of the `box model`. The first is the `content box` which is where the content is stored within the box. Second is the `padding box` which is white space used to pad around the content. Third is the `boarder box` which wraps around both the padding and the content. Lastly, the `margin box`, which is the outer layer, wraps around everything as white/invisible space.

__*Learn JS*__
__Arrays. Operators and Expressions. Conditionals. Loops.__

1. __What `<data types>` can you store inside of an `<Array>`__ Arrays can hold data types such as numbers, objects(null), strings, booleans, and so on.

2. __Is the `<people>` array a valid JavaScript array? If so, how can I access the values stored? If not, why?__

 `<const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];>`

 Yes it is a valid array. You can acess the stored values by using nested array indexing.

3. __List five shorthand operators for assignment in javascript and describe what they do.__ Five examples of shorthand operators for assignment are as follows. 1. x += f() which is used for Addition assignment and adds to two values. 2. x /= F is for the Division assignment which divides the values. 3. x **= f() which is for the Exponentiation assignment that raises one quantity to the power of another. 4.  x = f() is the basic assignment that assigns vales to the variables or properties. 5. x %= f() gives the remainder on the two operands and assigns the results to the left operand.

4. __Read the code below and evaluate the last `<expression>` and explain what the result would be and why.__

 `<let a = 10;>`
 `<let b = 'dog';>`
 `<let c = false;>`

 `<// evaluate this>`
 `<(a + c) + b;>`

 If a = 10, b = dog, and c = false (or 0 would be subsituted in javascript due to a type coercion mechanism), the expression would be (10 + 0) + dog and the result would be 10dog as you'd be adding 10 + 0 which is 10, and then adding dog to that. 

5. __Describe a real world example of when a conditional statement should be used in a JavaScript program.__ A real world example of a conditional statement could be if a supervisor asked you that if you worked extra hours overtime today, that they would give you those hours off tomorrow. so if you work 3 hours over today, they'll give you 3 hours off tomorrow. 

6. __Give an example of when a `<Loop>` is useful in JavaScript.__
Loops are useful if you will be doing the same thing repeatedly such as if you need a correct password to access a site. Until the password is correct, it will keep looping back to the login screen.