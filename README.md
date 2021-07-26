## _Password Checker_

#### This project is a password checker, it receives password as input and returns the number of times the password 
#### has been used

_Steps to building the password checker_

1. import all the necessary modules `requests` `hashlib` `sys`
   
2. define a function `requests_api_data` that  receives the password as input
   and returns the api for pawned passwords of the input using the `requests` module
   
3. define another function `get_password_leaks_count` that uses the `hashlib` to get counts in hash

4. define a function `def pwned_api_check` that receives password as input, hashes it, giving the number of counts 


`sys` allows one give arguments in the terminal
