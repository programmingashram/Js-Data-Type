In **Data types** describe the different types or kinds of data that we're working and storing in variables.

Js two types of data types

1. 🚥 **Primitive Data type**
    1. String
    2. Number
    3. Boolean
    4. Undefind
    5. Null  

2. 🚥 **Non Primitive Data type**
    1. Object
    2. Array
    3. Regular Expression
  

## Primitive Data Types 🎯

#### 💡 String (Privitive Types)
 
In string we can define our value in uder double and single quots.

> <code>let x = "Values";</code>

#### 💡 Number (Privitive Types)
 
In Number it wil start numerical values and without any quots.

> <code>let x = 10;</code>

#### 💡 Boolean (Privitive Types)
 
Boolean return <code>true</code> and <code>flase</code> only , true means 1, and false means 0;

> <code>let x = true;</code>

#### 💡 Undefind (Privitive Types)
 
if you're not assign any values in variable and you called id , so undefiend will return.

> <code>let x;</code>
> <code>console.log(x);</code>

#### 💡 Null (Privitive Types)
 
if we have'nt any number and data in our varaiable, in case we can assgin <code>null</code>. null is pre defind object in javascript.

> <code>let x = null;</code>


## Non Primitive Data Types 🎯


#### 💡 Object (Non Privitive Types)
 
in Object we can add and store multiple properties in a single time.

**For example

![alt text](https://img.icons8.com/emoji/2x/oncoming-automobile.png)

We have a car , and car is an object , its having multiple properties. like - 
Brand, Modal, Price, Color.

In case Js Object will allows us to storing these properties in single statement or variable.

<code>
    let car = {
        Brand : "Tata"
        Modal : "2019",
        Price : "5L",
        Color : "Black"
    }
</code>


#### 💡 Array (Non Privitive Types)
 
in Object we can add and store multiple values in a single time.

<code>
    let car = ["Ansh", "Rahgul", "Akram", ""Shivam];
</code>


#### 💡 Regular Exp. (Non Privitive Types)
 
Regular is an object, that allow us to create charecter block for matching and replacing and searching the content.
regular expression is mostly use in form validation.


##### ✨ Matching data.serach()
It will return us to charecter.

<code>
    let data = "Hii I am Programmer";
    let o = /am/g; 
    let result = data.match(o);
    console.log(result); output = [am, am]
</code>

##### ✨ Searching -  data.serach()
It will return us to indexing number where of is comming.

<code>
    let data = "Programming Ashram is our center";
    let o = /is/; 
    let result = data.search(o);
    console.log(result); // output = 19
</code>


