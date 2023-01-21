# NeoOS
A Operating System that runs a interpeted memory safe C# like language in ring 0

# The idea
- Write a 100% memory safe interpreted language in rust with simular syntax to C#
- Have it as the only binary in ring0
- Pass strings (not files) to the language kinda how a micro kernel passes messages between modules
- All other languages and programs would interface directly through this language
