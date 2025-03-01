Download link :https://programming.engineering/product/editdist-s-write-an-assembly-program-called-editdist-s-solution/

# Editdist.S-Write-an-assembly-program-called-editDist.s-Solution
Editdist.S Write an assembly program called editDist.s – Solution
Files to submit: editDist.s

Write an assembly program called editDist.s that calculates the edit distance between 2 strings. An explanation of what edit distance is can be found here while accompanying pseudo code can be found here.

The label for the first string should be string1 and the label for the second string should be string2.

The edit distance between string1 and string2 should be placed in EAX.

For each string please allocate space for 100 bytes.

While you must allocate space for 100 bytes in your final submission you will likely find it easier to work with the .string directive for testing and debugging.

AFTER the last line of code that you wish to be executed in your program please place the label done.

Make sure that there is an instruction after the done line and a new line after that instruction. If you don’t your output won’t match mine.

I have included a C implementation of the edit distance program. I highly recommend translating this solution into assembly as it will make your life much easier.

As a note remember that constants cannot be swapped. Pay careful attention to this in your solution

Use subroutines. It makes life easier (in my opinion)

I have included a Makefile that will compile your program. Your program must be able to be compiled by this Makefile when you submit it

IT IS OF VITAL IMPORTANCE THAT YOU NAME YOUR LABELS AS SPECIFIED AND MAKE THE APPROPRIATE AMOUNT OF SPACE FOR EACH VARIABLE! I will be using gdb to test your code and if your labels do not match then the tests will fail. You must also make sure to include the done label AFTER the last line of code you want executed in your program so that I know where to set break points.

