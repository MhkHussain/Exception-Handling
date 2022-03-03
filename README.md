# Exception-Handling
The main aim of the exception handling is to prevent potential failures and uncontrolled stops.
We can catch and handle an exception with a try-except block:
* try block contains the code to be monitored for the exceptions.
* except block contains what to be done if a specific exception occurs. If no exception occurs then this section is skipped and the try-except statement is concluded.
* If exception raised matches with the one specified in except keyword, the code inside the except block is executed to handle the exception.
* You can catch any exception if you do not specify any type of exception in the except keyword.
* try block execution is terminated when the first exception occurs.
* try-except block may have more than one except block to handle several different types of exceptions.
* Optional else block is executed only if there is no exception occurs in a try block. If any exception is raised, the else block will not be executed.
* Optional finally block is used for clean up code. This block is always executed.


![python-exception-handling](https://user-images.githubusercontent.com/86805669/156527725-c0b59f62-1c03-4c8d-9f5b-7692295c1ea8.png)
