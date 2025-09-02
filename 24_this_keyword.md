https://www.youtube.com/watch?v=9T4z98JcHR0&list=PLlasXeu85E9eWOpw9jxHOQyGMRiBZ60aX&index=8

1. "this" in global scope always points to the globalObject (globalObject depends on javascript runtime env, e.g. window, global)
2. "this" in a function depends on 2 things
   
    a. strict / non strict mode (in strict mode, "this" is undefined, in non strict mode, "this substitution" takes place and "this" points to globalObject)
   
    b. how the function is being invoked (if we invoke the function using the global object in strict mode, then "this" will point to that globalObject)
   
3. "this" in a method always points to the object that is used to invoke the method.
4. difference between function and method: a method is a function inside an object
5. ```call```, ```apply``` & ```bind``` are used to share a method with another object (hence the "this" keyword reference would also change accordingly)
6. "this" inside arrow function refers to the enclosing lexical context, arrow function don't provide their own ```this``` binding (e.g. global object)
7. "this" in DOM points to the HTML element itself on which it is being used


<img width="400" height="334" alt="Screenshot 2025-09-02 at 11 43 53 AM" src="https://github.com/user-attachments/assets/e836da12-f319-4b1e-8963-19b86df8b499" />

```call```
<img width="437" height="262" alt="Screenshot 2025-09-02 at 11 51 01 AM" src="https://github.com/user-attachments/assets/2264d156-2e8f-4e42-86e6-2c2841264e5a" />
1. call
Invokes the function immediately. You pass the this context and arguments one by one.
2. apply
Similar to call, but arguments are passed as an array. Useful when arguments are already in an array.
3. bind
Does not invoke immediately. Returns a new function with this permanently bound. You can call it later.

```call``` = "Call me now with these arguments"
```apply``` = "Apply the arguments from this array and call me now"
```bind``` = "Bind me to this person, and you can call me later"
<img width="687" height="485" alt="Screenshot 2025-09-02 at 11 57 27 AM" src="https://github.com/user-attachments/assets/940f2377-86a8-48d6-b74b-0471e2acc86f" />

