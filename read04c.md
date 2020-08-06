# Summary of Reading 04c

## Sync. and Async. JS
### Callbacks 
JS is a synchronous language, meaning that scripts are run line by line top to bottom. When one task is complete, it moves on to the next line/ task. Callbacks are away to take advantage of Async programming. We want async programming because it is more seamless for a user. Computers are meant to operate asynchronously -- meaning that while one task is being processed, the computer can still run and begin processing other tasks!

### Promises
Promise is a constructor `new Promise()`. After creating a new promise, you use it by stringing on `.then` methods that tell the program what to do depending on what the promise returns. I don't really understand fetch very well, however it is the equivelent as using a promise constructor, as in it works async. You can handle errors with it, meaning that if an error happens it'll catch it and pop out of the code block, then you can choose what to do with that error `err`. `Promise.all()` returns only when all code is done running and we have a returned value.

### More on Promises
Chaining on to promises has an advantage because because the `.then()` method returns a new promise, different from the original.