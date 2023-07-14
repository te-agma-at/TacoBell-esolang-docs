## Basic Keywords
<br>
These all start with the @ symbol and have different purposes, so basically like built-in functions
<br>
@toilet (variable-name) - Creates a new unassigned Variable and opens it to any line of code.
<br>
@shit (variable-name) (value) - Assigns a value to a Variable. (Can be strings, numbers (decimal OR integer), booleans, etc.)
<br>
@cook (variable-name) (type) - Casts a Type to a Variable
<br>
@serve (ascii-value) - Prints a character with the Ascii Value given onto the Output Table
<br>
@maintenance (number-value) - Halts any code that is currently running for a given number of seconds.
<br>
@clog (variable-name) (constant-value) - Assigns a constant value to a Variable.
<br>
@morebeef (variable1-name) (variable2-name) - Performs a greater-than comparison operation between the two Variables given
<br>
@lessbeef (variable1-name) (variable2-name) - Performs a less-than comparison operation between the two Variables given
<br>
@equalbeef (variable1-name) (variable2-name) - Performs an equal-to comparison operation between the two Variables given
<br>
@order (taco-name) - Calls a !taco code block

## Code Blocks
### "foodrush"
!foodrush ((variable-name) >> (min-range)..(max-range)) {
<br>


}
<br>


These blocks are like "for" loops, iterating the code below a specific given amount of times when assigned a variable to iterate and increment over.
### "task"
!task ((condition)) {
<br>


}
<br>


These blocks are like "if-then" blocks, only running the code within it if the condition above results to TRUE
### "taco"
!taco ((parameters)) {
<br>


}
<br>


"taco" blocks are basically functions; they run the code within it when it is called using the @order keyword.


