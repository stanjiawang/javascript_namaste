https://www.youtube.com/watch?v=DlTVt1rZjIo&list=PLlasXeu85E9eWOpw9jxHOQyGMRiBZ60aX&index=5

1. Promises APIs are crucial for interviews and everyday application development, especially when handling asynchronous operations like parallel API calls.
2. ```Promise.all``` handles multiple promises simultaneously, returning an array of results when all promises are fulfilled, and throwing an error if any promise fails.
3. If any promise in ```Promise.all``` fails, the entire operation fails, and an error is thrown immediately without waiting for other promises.
4. ```Promise.allSettled``` waits for all promises to settle (whether fulfilled or rejected) before returning an array of results or errors, making it suitable for scenarios where partial failures are acceptable.
5. ```Promise.race``` returns the result of the first settled promise, whether it's success or failure, making it ideal for scenarios where the fastest response is required.
6. ```Promise.any``` is similar to Promise.race but waits for the first successful promise rather than the first settled one, making it suitable for scenarios where success is prioritized over speed.
7. ```Promise.any``` returns the result of the first successful promise and ignores subsequent failures, waiting for success.
8. ```Promise.any``` collects errors if all promises fail and returns an aggregated error array.
9. ```Promise.all``` returns an array of all results when all promises succeed, waiting for all to finish.
10. ```Promise.allSettled``` waits for all promises to settle (succeed or fail) before returning results, ensuring all promises are accounted for.
11. ```Promise.race``` returns the result of the first settled promise, whether success or failure, racing to return the fastest result.
12. ```Promise status``` can be checked for rejection along with the reason for rejection, providing clarity in handling errors.
13. ```Promise.race``` returns the result of the first settled promise, whether it's a success or failure, regardless of the order in which promises are fulfilled.
14. Explaining concepts in interviews requires not only understanding but also the ability to articulate ideas clearly, which is often a stumbling block for many candidates.
15. ```Promise.race``` resolves to the value/error of the first settled promise, regardless of success or failure, emphasizing the importance of understanding terminology in the Promise world.
16. Familiarity with Promise terminology like ```"settled," "resolved," "rejected," "fulfilled," and "rejected"``` is crucial for effectively working with Promise APIs.
17. ```Promise.any``` waits for the first settled promise, and if it's a success, returns the result, ignoring subsequent rejections until a success occurs.
18. When all promises fail with Promise.any, it results in an "aggregate error," which consolidates all the errors encountered during execution.
19. Handling aggregate errors in Promise.any involves accessing the errors in an array format, allowing for comprehensive error management and analysis.
<img width="1213" height="945" alt="Screenshot 2025-08-29 at 12 41 24 PM" src="https://github.com/user-attachments/assets/54282a17-de70-402a-b55f-208260b2f1f2" />
```Promise.all``` all or nothing, one failure, all failure. Failed fast. If all success, return a list of all success, [res1, res2, res3].
<img width="1326" height="684" alt="Screenshot 2025-08-29 at 12 43 17 PM" src="https://github.com/user-attachments/assets/c60ca32e-5e2c-4d0e-9149-741eec1e743f" />
```Promise.allSettled``` will wait for all settled no matter success of fail. Return all result no matter success or failure.
<img width="1245" height="848" alt="Screenshot 2025-08-29 at 12 45 42 PM" src="https://github.com/user-attachments/assets/287bf68a-5b4a-4452-ad32-c29e33ea950a" />
```Promise.race``` return the first settled value, no matter success or failure. it could settled with either success or failure.
<img width="1211" height="713" alt="Screenshot 2025-08-29 at 12 48 56 PM" src="https://github.com/user-attachments/assets/925830dd-5380-4b40-b0b2-20715d73a790" />
```Promise.any``` return the first success, ignore the failure before success. If all failed, return a aggregate error, a list of all errors: [err1, err2, err3]

