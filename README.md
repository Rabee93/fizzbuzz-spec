# fizzbuzz test
This test will return "fizz" if the number is divisible by 3, it will return "buzz" if the number is divisble by 5 and it will return "fizzbuzz" if the number is divisible by 3 and 5. Otherwise it will return the number.

## Getting started
``` 
git clone https://github.com/Rabee93/fizzbuzz-spec.git
```
## Usage
- type irb in the command line.
- require the fizzbuzz file by typing 
``` require_relative "lib/fizzbuzz"```
- call the fizzbuzz method on the number that you want to test.e.g ```fizzbuzz 3``` should give you "fizz" etc
- exit irb by typing "exit"

## Running tests

 type in the command line
```rspec spec/fizzbuzz_spec.rb```
