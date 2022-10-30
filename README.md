		 AirBnB clone

		DESCRIPTION 

This is the first step towards building our first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

1. Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances

2. Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

3. Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

4. Create the first abstracted storage engine of the project: File storagecreate all unittests to validate all our classes and storage engine

		LEARNING OBJECTIVES

1. How to create a Python package

2. How to create a command interpreter in Python using the cmd module

3. What is Unit testing and how to implement it in a large project

4. How to serialize and deserialize a Class

5. How to write and read a JSON file

6. How to manage datetime

7. What is an UUID

8. What is *args and how to use it

9. What is **kwargs and how to use it

10. How to handle named arguments in a function

		REQUIREMENTS

		Python Scripts

1. Allowed editors: vi, vim, emacs

2. All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)

3. All your files should end with a new line

4. The first line of all your files should be exactly #!/usr/bin/python3

5. Your code should use the pycodestyle (version 2.8.*)

6. All your files must be executable

7. The length of your files will be tested using wc

8. All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')

9. All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')

10. All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')


		Python Unit Tests 

1. All your files should end with a new line

2. All your test files should be inside a folder tests

3. You have to use the unittest module

4. All your test files should be python files (extension: .py)

5. All your test files and folders should start by test_

6. Your file organization in the tests folder should be the same as your project

e.g., For models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py

e.g., For models/user.py, unit tests must be in: tests/test_models/test_user.py

7. All your tests should be executed by using this command: python3 -m unittest discover tests

8. You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py

9. All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')

10. All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')

11. All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')

