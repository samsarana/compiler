# compiler
A compiler written in python to compile a program in a rudimentary language to JVM bytecode. The rudimentary language has a grammar that supports basic assignment, arithmetic, if/if-else/while statements and nested Boolean comparisons.

Here are some examples of programs in the language that can be compiled:

Example 1
z := 2;
if z < 1 then
  z := 1
else
  z := 9
end;
write z

Example 2
read n;
sum := 0;
while n > 0 do
  sum := sum + n;
  n := n - 1
end;
write sum

Example 3
x := 10;
y := 2;
if x > 9 and x < 11 or x != 4 then
   write 1
end
