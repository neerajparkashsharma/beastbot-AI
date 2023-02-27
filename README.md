# BeastBot-AI

BeastBot AI is a simple AI-based animal guessing game. The program uses an expert system algorithm to guess the name of an animal based on a set of yes-or-no questions.

## Installation
* Clone the repository to your local machine using the command: `git clone https://github.com/neerajparkashsharma/BeastBot-AI.git`
* Open the project in your preferred Java IDE.
* Run the Main.java file.


## Usage
* When you run the program, you will be asked to think of an animal and then answer a series of yes-or-no questions about it.
* After answering each question, the program will try to guess the animal based on your responses.
* If the program correctly guesses the animal, it will display the name of the animal.
* If the program is unable to guess the animal, it will display a message indicating that the animal does not exist.


## Updating the Code
If you would like to optimize or update the code, you can modify the take_input method in the Main.java file. This method takes in an integer answer, a string property, and an ArrayList of HashMaps with String keys and Object values named database. The method filters the database based on whether the value associated with property is equal to answer, and then outputs the name of the animal if there is only one animal left in the database.



### Enjoy playing BeastBot-AI!
