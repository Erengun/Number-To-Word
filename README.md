# Number-To-Word
Convert number to any language made @42

• Create a program that takes a number as argument and converts it to its written
letters value.

• Executable name: rush-02

• Your source code will be compiled as follows :

make fclean

make

• Your program can take up to 2 arguments:

◦ If there is only one argument, it is the value you need to convert

◦ If there is two arguments, the first argument is the new reference dictionnary
and the second argument is the value you need to convert.

• If the argument isn’t a valid positive integer, your program must return "Error",
followed by a newline.

• Your program must parse the dictionnary given as resource to the project. The
values inside it must be used to print the result. These values can be modified.

• Any memory allocated on the heap (with malloc(3)) must be freed correctly. This
will be verified during evaluation.

• The dictionnary will have the following rules.

C Piscine Rush 02
[a number][0 to n spaces]:[0 to n spaces][any printable characters]\n

◦ You will trim the spaces before and after the value in the dictionnary.

◦ The dictionnary will always have at least the keys as in the reference dictionnary. Their value can be modified, more entries can be added, but the initial
keys can’t be removed.

◦ You only need to use the initial entries (For instance, if we add 54: fifty-four,
you still have to use 50: fifty and 4: four)

◦ The entries of the dictionnary can be stored in any order.

◦ There can be empty lines in the dictionnary.

◦ If you have any errors from the dictionnary parsing, your program must output
"Dict Error\n"

◦ If the dictionnary doesn’t allow you to resolve the asked value, your program
must output "Dict Error\n".
