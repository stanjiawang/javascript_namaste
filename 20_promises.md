https://www.youtube.com/watch?v=ap-6PPAuK1Y&list=PLlasXeu85E9eWOpw9jxHOQyGMRiBZ60aX&index=3

1. Before promise we used to depend on callback functions which would result in
   1.) Callback Hell (Pyramid of doom)
   2.) Inversion of control
2. Inversion of control is overcome by using promise.
   
a. A promise is an object that represents eventual completion/failure of an asynchronous operation.

b. A promise has 3 states: pending | fulfilled | rejected.

c. As soon as promise is fulfilled/rejected => It updates the empty object which is assigned undefined in pending state.

d. A promise resolves only once and it is immutable. 

3. Using .then() we can control when we call the cb(callback) function.
4. To avoid callback hell (Pyramid of doom) => We use promise chaining. This way our code expands vertically instead of horizontally. Chaining is done using '.then()'
5. A very common mistake that developers do is not returning a value during chaining of promises. Always remember to return a value. This returned value will be used by the next .then()
