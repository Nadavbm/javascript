## javascript cheatsheet

``` // one line comment ```
```
/*
multi line comment
*/
```

### variables

``` 
var a;
var b = "string";
var c = 1 + 2 +3;
var t = true;
var arr = [2,5,1,4];
var h =function(){};
```

``` var ``` - common variable that can be reassigned but only accessed within a function.

``` const ``` - var which cannot be reassigned. 

``` let ``` - var that can be reassigned but declared only once in the code

```
var age = 36
const pi = 3.14
let it = "be"
```

#### data types

``` var someInt = 3 ``` number

``` var str = "Stringi ririr" ``` string

``` var wahad = true ``` boolean

``` var vornachname = {vorname:"Mo", nachname:"Vie"} ``` object

``` undefined, null, Infinty ``` special

#### operators

```
a = b + x - z;
a = b * (x / y);
x = 100%21;
i++; j++;
```

##### logical operators

``` & ``` and

``` | ``` or

``` ~ ``` not

``` ^ ``` xor

##### arithmetic operators

``` a * (b+c); ``` grouping

``` attribute.object ``` member

``` object[arrval] ```member

``` !(t == f) ``` logical not

``` a != b ``` not equal

``` x === y ``` strict equal

``` x !== y ``` string unequal

``` typeof obj ``` type (number, object, function)

``` x < y ``` ``` x > y ``` less and greater than

``` z <= g ``` ``` z => g ``` less or equal, greater or equal

``` x += y``` this will be x = x + y ``` 2 += 5 ``` this equal 7

``` a && b ``` logical and ``` b || c ``` logical or 

### conditional statements

``` if (condition) {doSomething;} else {doSomethingElse;} ``` if has logical condition, in block {executed if the condition is true} else {in else block, execute if the condition is false}  

```
if ((age >= 90) && (age < 130)) {
    hasCorona = true;    
} else {
    hasCorona = false;
}
```

#### switch statement

```
switch (someInput) {
    case "blablabla":
        bla = "bla"
        break;
    case "romromrom":
        rom = "rom"
        break;
    default:
        eating = "Kebab!";
}
```

### loops

for loops:
```
for (var = i; i < 10; i++) {
    document.write(i + "= `{i}`" + "<br />" );
}
```

```
arr = [23,1234,4532,6543,1234,12342453,123,3241];
var sum = 0;
for (var i = 0; i < arr.length; i++) {
    sum += arr[i];
}
```

while loop:
```
var i = 23;
while (i < 100) {
    i *= 2;
    console.log(i + "<br />");
}
```

do while loop:
```
var i = 1;
do {
    i *= 2;
    console.log(i + ",");
} while (i < 2000)
```

break
```
for (var i = 0; i < 100; i ++) {
    if (i == 42) { break; }
    document.write(i + ",");
}
```

continue 
```
for (var j = 23; i < 100; i++) {
    if (i == 44) { continue; }
    console.log(i + ",")
}
```

### arrays


### global functions


#### methods


### error handling


### json


### promise


### dates


### regular expressions


### string manipulation



### math