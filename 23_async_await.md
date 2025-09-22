https://www.youtube.com/watch?v=6nv3qy3oNkc&list=PLlasXeu85E9eWOpw9jxHOQyGMRiBZ60aX&index=6

1. ```async/await``` used for handling promises
2. ```async``` always return a promise,  use ```async``` before a promise, and it will resolve the promise. ```const val = await promise```
3. ```await``` can only used inside an async function
4. Can only write ```await``` keyword infront of a promise
5. Major difference: the await will wait for the promise to be resolved, then execute the next line. Don't need promise chain like ```.then().then().then()...```
6. If there are two/all await in one function, the two/all await will be resolved at the same time if the following 
7. While awaiting JS Engine does not actually wait rather the function is suspended and call stack is free for other stuffs but it looks like program is waiting at that point
8. Use try catch for Error handling and can also use  ```.catch()``` method
9. ```fetch``` API will return a promise, fetch(URL) => response.json() => jsonValue

```
const myAsyncFunction = async () => {
  try {
    const data = await fetchData();
    console.log("Data:", data);
  } catch (err) {
    console.error("Error:", err);
  }
};
```

<img width="639" height="329" alt="Screenshot 2025-09-02 at 10 53 31 AM" src="https://github.com/user-attachments/assets/f4754159-d9a8-41b6-9747-1e51187e7b79" />
<img width="613" height="428" alt="Screenshot 2025-09-02 at 10 58 45 AM" src="https://github.com/user-attachments/assets/3fae5157-e14c-4398-a098-d2ab805e57cd" />
