https://www.youtube.com/watch?v=nqsPmuicJJc&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=20

1. The setTimeout function stores it in the callback queue which is executed only after call stack is empty, even if setTimeout is set to 0ms. 
2. setTimeout ensures that minimum it will take the time mentioned because it may be paused due to call stack not empty.

```
setTimeout(() => {
  console.log("Hello after 2 seconds!");
}, 2000);
```
