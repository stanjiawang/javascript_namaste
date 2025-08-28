https://www.youtube.com/watch?v=QCRpVw2KXf8&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=7
1. Reserves the memory space specifically for GEC to be created in stack
2. GEC(Global Execution Context) is created
3. Creates a 'Window': a javascript 'global object' which 'runs with GEC' with an object whose values are in global scope(can be accessed by using any of the key in 1:37 )
4. js object 'this' is created (really the name is 'this') and this level this=== window
5. then our script starts execution
The variable in javascript always assigns its value from Global level (unless specified earlier 'in the script' itself or in function)
