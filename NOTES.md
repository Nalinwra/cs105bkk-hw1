# HW1 notes

Answer each question in a few sentences. Be specific: name the function, the error or the command.

## What did you try?
I tried to implement the MenuItem, PromoItem, and Order classes. I also wrote the cheapest() function and tested the program using pytest.
## What broke, and how did you fix it?
I made a mistake in the Order class constructor by writing self.line instead of self.lines. This caused an error because the other methods used self.lines. I fixed it by changing the variable name to self.lines.
## What would you do differently next time?
Next time, I will check my variable names carefully and test each function separately before running all the tests. I will also read error messages more carefully to find and fix bugs faster.