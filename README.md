# AirBnB clone - The console Project

This project is a simple clone of the AirBnB website. It implements a backend interface or console to manage program data like a shell. Console commands allow users to create, update, destroy objects, and manage file storage.

## Project Structure
- Implemented a parent class (BaseModel) to handle future instances' initialization, serialization, and deserialization.
- Created a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Developed all classes used for AirBnB (User, State, City, Place…) inherited from BaseModel.
- Created the first abstracted storage engine for the project: File storage.
- Wrote all unittests to validate all classes and the storage engine.

## Description of the command interpreter
The command interpreter helps manage the objects of the project by:

- Creating a new object (e.g., a new user or place).
- Retrieving an object from a file, a database, etc.
- Performing operations on objects (e.g., counting, computing stats, etc.).
- Updating attributes of an object.
- Destroying an object.

## How to start the interpreter

1. Prerequisites
> Python 3.0

2. Installation
#### Clone the repository:
git clone https://github.com/Daniel-IRYIVUZE/alu-AirBnB_clone.git

3. To start the interpreter:

#### Navigate to the project directory and run the command:
./console.py

#### Once in the console, use the 'help' command to view the list of available commands:
(hbnb) help

4. Exiting the Interpreter

#### To exit the console, simply type:

(hbnb) quit

#### How to Use the Interpreter
> To use the interpreter, follow these steps:

- Launch the console by running ./console.py.
- You will see a prompt (hbnb) indicating that the console is ready to accept commands.
- Use the documented commands to perform various operations on objects.
- When you're done, type quit or exit to exit the console.

#### Running Tests

> To run all the tests, execute the following command:

$ python3 -m unittest discover tests

> You can also run a single test by specifying the test file:

$ python3 -m unittest tests/test_models/test_city.py

## Authors
- [`Daniel Iryivuze`](https://www.linkedin.com/in/daniel-iryivuze-992141278/)
- [`Cysron Bugingo`](https://www.linkedin.com/in/)
