Here are some tricky JavaScript coding questions to challenge your skills:

1. **Variable Scope**:
   ```javascript
   var x = 1;
   function foo() {
       var x = 2;
       function bar() {
           x++;
           console.log(x);
       }
       bar();
   }
   foo();
   ```
   What will be logged to the console?

2. **Closure and Loop**:
   ```javascript
   for (var i = 0; i < 5; i++) {
       setTimeout(function() {
           console.log(i);
       }, 100);
   }
   ```
   What will be logged to the console?

3. **Object and Array Comparison**:
   ```javascript
   const obj1 = { name: 'Alice' };
   const obj2 = { name: 'Alice' };
   const arr1 = [1, 2, 3];
   const arr2 = [1, 2, 3];
   console.log(obj1 === obj2);
   console.log(arr1 === arr2);
   ```
   What will be the output and why?

4. **`this` Keyword**:
   ```javascript
   const obj = {
       value: 10,
       increment: function() {
           setTimeout(function() {
               this.value++;
               console.log(this.value);
           }, 1000);
       }
   };
   obj.increment();
   ```
   What will be logged to the console after one second?

5. **Function Hoisting**:
   ```javascript
   console.log(foo()); // What will this log?
   var foo = function() {
       return 'Hello, World!';
   };
   ```

6. **Promise and Async/Await**:
   ```javascript
   async function example() {
       return 'First';
   }
   example().then(console.log);
   console.log('Second');
   ```
   In what order will the outputs appear in the console?

Feel free to dive deeper into any of these questions or ask for clarifications!
