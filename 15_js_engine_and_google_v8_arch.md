https://www.youtube.com/watch?v=2WJL19wDH68&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=19

1. JS runtime environment contains all elements required to run JS.
2. It contains JS engine, set of API's, callback queue, microtask queue, event loop.
3. JS engine is a piece of code.
4. Process includes Parsing ---> Compilation -----> Execution.
5. Parsing breaks code into tokens and converts it into AST(Abstract Syntax Tree).
6. Modern JS engine follows JIT(Just in time) compilation, it interprets while it optimises code as much as it can. (combine Interpretter and Complier)
7. Execution and Compilation are done together.
8. Execution has Garbage collector and other optimisation such as inlining, copy elusion, inline caching etc.
   
<img width="1265" height="897" alt="Screenshot 2025-08-27 at 12 28 38 PM" src="https://github.com/user-attachments/assets/2e9d1f28-da42-46f9-bc3b-e96bd1a4606f" />
AST: Abstract Syntax Tree astexplorer.net
<img width="1224" height="791" alt="Screenshot 2025-08-27 at 12 29 24 PM" src="https://github.com/user-attachments/assets/dccca8b4-c021-412b-9f17-17246af21f2f" />
JIT compllation (Just in time)
<img width="1305" height="970" alt="Screenshot 2025-08-27 at 12 32 19 PM" src="https://github.com/user-attachments/assets/3bc01854-33a3-4917-b4a6-0fead533340c" />
<img width="867" height="601" alt="Screenshot 2025-08-27 at 12 36 50 PM" src="https://github.com/user-attachments/assets/b38c8ff2-4109-4fdd-a7cc-0013e7e6996e" />
<img width="770" height="577" alt="Screenshot 2025-08-27 at 12 39 36 PM" src="https://github.com/user-attachments/assets/62fb3a5f-3fcb-402c-806e-c80b59f3204b" />

Mark and Sweep for garbage collection 
