# Direct Modification of Instance Variables in Ruby

This example showcases a common, yet subtle, error in Ruby: directly manipulating instance variables using `instance_variable_set` or `instance_variable_get`. While technically possible, it undermines the principles of encapsulation and can lead to unexpected issues.

The included `bug.rb` file demonstrates the problem.  The `bugSolution.rb` file provides a more robust approach.