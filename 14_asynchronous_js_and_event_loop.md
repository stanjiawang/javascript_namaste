https://www.youtube.com/watch?v=8zKuNo4ay8E&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=18

1. Browser has superpowers that are lent to JS engine to execute some tasks, these superpowers include web API's such as console, location, DOM API, setTimeout, fetch, local storage.
2. Callback functions and event handers are first stored in Web API environment and then transferred to callback queue.
3. Promises and mutation observer are stored in API environment and then transferred to microtask queue.
4. Event loop continuously observes call stack and when it is empty it transfers task to call stack.
5. Micro task is given priority over callback tasks.
6. Too many micro tasks generated can cause Starvation (nit giving time to callback tasks to execute).

<img width="1373" height="894" alt="Screenshot 2025-08-27 at 11 30 20 AM" src="https://github.com/user-attachments/assets/ba1fc43a-ccf8-4471-8bc5-1f1b146c7341" />
<img width="1405" height="1011" alt="Screenshot 2025-08-27 at 11 34 03 AM" src="https://github.com/user-attachments/assets/9afe95ab-61ba-4195-955c-68960b41401c" />
<img width="1526" height="1053" alt="Screenshot 2025-08-27 at 11 53 23 AM" src="https://github.com/user-attachments/assets/0589f239-f841-4b3f-a2c6-1ee40590c9ff" />
<img width="1184" height="408" alt="Screenshot 2025-08-27 at 11 54 33 AM" src="https://github.com/user-attachments/assets/3bbd39cf-ab05-4a00-a09d-e2f2fc8cf0c7" />
Promoises, MutationObserver has higher priority, in Microtask Queue.
The other queue is callback queue(Task queue).
