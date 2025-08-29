https://www.youtube.com/watch?v=ap-6PPAuK1Y&list=PLlasXeu85E9eWOpw9jxHOQyGMRiBZ60aX&index=3

1. Before promise we used to depend on callback functions which would result in
   
   a. Callback Hell (Pyramid of doom)
   
   b. Inversion of control
2. Inversion of control is overcome by using promise.
   
   a. A promise is an object that represents eventual completion/failure of an asynchronous operation.
   
   b. A promise has 3 states: pending | fulfilled | rejected.
   
   c. As soon as promise is fulfilled/rejected => It updates the empty object which is assigned undefined in pending state.
   
   d. A promise resolves only once and it is immutable. 

3. Using .then() we can control when we call the cb(callback) function.
4. To avoid callback hell (Pyramid of doom) => We use promise chaining. This way our code expands vertically instead of horizontally. Chaining is done using '.then()'
5. A very common mistake that developers do is not returning a value during chaining of promises. Always remember to return a value. This returned value will be used by the next .then()
<img width="564" height="290" alt="Screenshot 2025-08-29 at 10 49 42 AM" src="https://github.com/user-attachments/assets/ad21ca72-172f-41a7-8e13-48803709ada0" />
<img width="739" height="331" alt="Screenshot 2025-08-29 at 10 58 09 AM" src="https://github.com/user-attachments/assets/002af69f-adff-4712-89d0-484bdf6da4f2" />

Promise is nothing but an object,
```
Prototype: Promise
PromiseState: pending/fulfilled/rejected
PromiseResult: undefine/Response
```

