Description 
AirBnB Clone is a complete web application, integrating database storage, a back-end API, and front-end interface in a clone of AirBnB.

This team project is part of the Alx School Software Engineering program.
It represents the first step towards building a full web application.

This first step consists of:

a custom command-line interface for data management,
and the base classes for the storage of this data.

Usage
The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.

Command	Example
1. Run the console	./console.py
2. Quit the console	(hbnb) quit
3. Display the help for a command	(hbnb) help <command>
4. Create an object (prints its id)	(hbnb) create <class>
5. Show an object	(hbnb) show <class> <id> or (hbnb) <class>.show(<id>)
6. Destroy an object	(hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)
7. Show all objects, or all instances of a class	(hbnb) all or (hbnb) all <class>
8. Update an attribute of an object	(hbnb) update <class> <id> <attribute name> "<attribute value>" or (hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")

Interactive mode (example)

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$

Non-interactive mode (example)
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
Testing
Unittests for the AirBnB project are defined in the tests folder. To run the entire test suite simultaneously, execute the following command:
$ python3 unittest -m discover tests

Alternatively, you can specify a single test file to run at a time:
$ python3 unittest -m tests/test_console.py

AUTHORS
Awoseemo Babajide
Salako Fisayo
