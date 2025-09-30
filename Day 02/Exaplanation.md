Explanation (Line by Line)

let name = "Abhay";

Creates a variable name using let.

Stores a string value "Abhay".

let age = 23;

Creates a variable age.

Stores a number value 23.

const country = "India";

Creates a variable country using const.

const = fixed value (cannot be changed later).

var city = "Vadodara";

Old way of making variables.

Works like let but has some issues with scope (we use let now).

console.log(...)

Prints the values in the console.

Example output:

Name: Abhay
Age: 23
Country: India
City: Vadodara


Updating a variable

age = 24; → allowed because age was declared with let.

console.log("Updated Age:", age); → prints Updated Age: 24.

Trying to update const

If we try country = "USA"; → ❌ Error (because const cannot be changed).

👉 So in short:

let → changeable, modern way.

const → fixed value.

var → old way, avoid in new code.