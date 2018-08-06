# Primitive Data Type
## JS Data Types: Primitives  
The latest ECMAScript standard defines 6 primitive data types:

* **Boolean:** Boolean represents a logical entity and can have two values: true, and false.
* **Null:** The Null type has exactly one value: null. <Never happens on its own, you intentionally set it to null>
* **Undefined:** A variable that has not been assigned a value has the value undefined.
* **Number:** [0 - 9], . ,  any combination, NaN, Inf
* **String:** anything
* **Symbol (new in ECMAScript 2015):**


*Anything followed by VOID turns it to Undefined*  
*Nothing can be converted to NULL*  
*TypeOf is an operator*  
*toString is an operator*  

## Learning Objective
To study primitive data types.

## Study Snippet
```Javascript
typeof (typeof Number(void Boolean(null))).toString();
    // s0: (Null, null)
    Boolean(null);
    // s1: (Boolean, false)
    void false;
    // s2: (Undefined, undefined)
    Number(undefined);
    // s3: (Number, NaN)
    (typeof NaN);
    // s4: (String, "number")
    ("number").toString();
    // s5: (String, "number")
    typeof "number";
    // s6: (String, "string")
 ```
 
 ## Exercises
* ```Javascript
    typeof (typeof Number(void Boolean(null))).toString();
    void false;
    (typeof NaN);
    Boolean(null);
    typeof "number";
    Number(undefined);
    ("number").toString();
 ```
 * ```Javascript
  // s0: (Null, null)

    // s1: (Boolean, false)

    // s2: (Undefined, undefined)

    // s3: (Number, NaN)

    // s4: (String, "number")

    // s5: (String, "number")
 ```
 ## Helpful Links
 
 * [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)  
 * [W3Schools](https://www.w3schools.com/js/js_datatypes.asp)

