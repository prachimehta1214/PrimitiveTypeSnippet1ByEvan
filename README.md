# Primitive Type Snippet1 By Evan
**JS Data Types: Primitives**
___
The latest ECMAScript standard defines 6 primitive data types:

**Boolean:**
**Null:**
**Undefined:**
**Number:**
**String:**
**Symbol (new in ECMAScript 2015):**
Undefined: undefined <Undefined can happen as an error also>
Null: No Value represented by NULL <Never happens on its own, you intentionally set it to null>
Strings: “anything"
Numbers: [0 - 9], . ,  any combination, NaN, Inf
Boolean: True or False


Anything followed by VOID turns it to Undefined

Nothing can be converted to NULL


TypeOf is an operator: 
toString is an operator:

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

