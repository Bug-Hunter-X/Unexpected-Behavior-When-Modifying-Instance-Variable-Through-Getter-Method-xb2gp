# Ruby Bug: Unexpected Instance Variable Modification

This repository demonstrates an uncommon bug in Ruby related to instance variable modification through getter methods.  The code shows how assigning a value to a getter method doesn't directly update the underlying instance variable.

The `bug.rb` file contains the buggy code. The `bugSolution.rb` file presents a solution by creating a setter method.

This is a subtle error that can be difficult to track down. Understanding how instance variables and methods interact in Ruby is crucial for avoiding this kind of issue.