# AdventOfCode2024_Day03
 Advent of Code 2024 - Day 03
 
## Part 03A

TMy job is to consume a big piece of text which include variety of random characters.
In that text, we need to extract the specific type of text with following formula: mul(X,Y) where X and Y are each 1-3 digit numbers. For instance, mul(44,46) multiplies 44 by 46 to get a result of 2024. Similarly, mul(123,4) would multiply 123 by 4.
However, because the text has been corrupted, there are also many invalid characters that should be ignored, even if they look like part of a mul instruction. Sequences like mul(4*, mul(6,9!, ?(12,34), or mul ( 2 , 4 ) do nothing.

For example, consider the following section of corrupted memory:

xmul(2,4)%&mul[3,7]!@^do_not_mul(5,5)+mul(32,64]then(mul(11,8)mul(8,5))
Only the four valid text are real mul instructions: mul(2,4), mul(5,5), mul(11,8), mul(8,5). Adding up the result of each instruction produces 161 (2*4 + 5*5 + 11*8 + 8*5).

Our objective is to get final result of all the multiplications. The whole text is provided in attached file called input.txt

