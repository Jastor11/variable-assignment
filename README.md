# Variable Assignment

## Objectives

1. Assign a local variable.

## Instructions

You will assign a local variable named `greeting` that is equal to `"Hello World"`.

First, we need to setup our testing suite by installing a ruby gem! A gem is a package of code some talented developer wrote for public use.

We can bring our testing gem - rspec - into our project by typing `gem install rspec` into our terminal.

Then, we can run our first tests by simply typing `rspec` into the terminal.

Doing so should produce this result:

```
Failures:

  1) ./variable.rb defined a local variable called greeting and set it equal to 'Hello World'
     Failure/Error: greeting = get_variable_from_file('./variable.rb', "greeting")
     NameError:
       local variable `greeting' not defined in ./variable.rb.
     # ./spec/spec_helper.rb:14:in `rescue in get_variable_from_file'
     # ./spec/spec_helper.rb:11:in `get_variable_from_file'
     # ./spec/variable_spec.rb:5:in `block (2 levels) in <top (required)>'

Finished in 0.00075 seconds (files took 0.0839 seconds to load)
1 example, 1 failure
```

To correct the failed test, create a variable named `greeting` in the `variable.rb` file. Set `greeting` equal to the string `"Hello World"`. 

Run `rspec` once more to test yourself.

Congratulations on your first ruby lab!