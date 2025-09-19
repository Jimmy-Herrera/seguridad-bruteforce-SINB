Program Description:
The program was created to implement a brute force attack to crack passwords of up to three digits.
The program will ask the user to enter a password and will systematically try all possible combinations of uppercase letters, lowercase letters, numbers, and symbols.
During execution, the program will record how many attempts it has made to find the correct password, as well as the time elapsed until the program manages to find the correct password. Finally, a graph is generated showing how the search time varies according to the complexity of the password.

How to run the program:
To run the program, we first need to have everything in order, that is, have Python installed on our computers, have a programming IDE—which in my case was VSCode—make sure we have the complete code without errors, and, once everything is in order, in the upper right corner we will find an icon that says “run”; we click on it and the program will start running.

Output examples:
Below, I will present some of the examples I used to check that my program was working correctly:
Ingresa una contraseña de máximo 3 caracteres: abc
Contraseña encontrada: abc
Intentos realizados: 104
Tiempo transcurrido: 0.0001 segundos
And its corresponding graph.
Another example, but this time with uppercase letters, numbers, and characters, is as follows: 
Ingresa una contraseña de máximo 3 caracteres: A7*
Contraseña encontrada: A7*
Intentos realizados: 268004
Tiempo transcurrido: 0.0645 segundos
And its corresponding graph.

Next, I will show what happens if the password has fewer than three characters:
Ingresa una contraseña de máximo 3 caracteres: aa
La contraseña tiene menos caracteres
And finally, I will show what happens if the password contains more than three characters:
Ingresa una contraseña de máximo 3 caracteres: aaa5
La contraseña tiene más caracteres
What if the password has 8 or more characters and uses uppercase letters, numbers, and symbols?
If we consider a password of eight or more characters that includes uppercase letters, numbers, and symbols, the number of possible combinations increases, making the time required for a brute force attack, similar to the one we created, practically impossible with common hardware.
