# middleW

Build a middleware using echo framework
First of all, you should create a handler which sends how many days left until 1 Jan 2025 and response with HTTP 200 OK status code.

Secondly, build a middleware, which checks HTTP header "User-Role" presents and contains "admin" and prints "it's admin" to the console (using default log package or any 3rd party) if so.
