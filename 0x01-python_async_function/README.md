Project: Python - Python - Async
Author: Samuel Atiemo

Project Tasks:

0. The basics of async
mandatory
Write an asynchronous coroutine that takes in an integer argument (max_delay, with a default value of 10) named wait_random that waits for a random delay between 0 and max_delay (included and float value) seconds and eventually returns it.

1. Let's execute multiple coroutines at the same time with async
mandatory
Import wait_random from the previous python file that you’ve written and write an async routine called wait_n that takes in 2 int arguments (in this order): n and max_delay. You will spawn wait_random n times with the specified max_delay.

2. Measure the runtime
mandatory
From the previous file, import wait_n into 2-measure_runtime.py.

3. Tasks
mandatory
Import wait_random from 0-basic_async_syntax.

Write a function (do not create an async function, use the regular function syntax to do this) task_wait_random that takes an integer max_delay and returns a asyncio.Task.

4. Tasks
mandatory
Take the code from wait_n and alter it into a new function task_wait_n. The code is nearly identical to wait_n except task_wait_random is being called.


