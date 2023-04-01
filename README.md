# Simon Memory Game

Simon is a memory game where you have to repeat the sequence of colors that the computer shows. The sequence gets longer each time you get it right. If you get it wrong, you lose.

## Development approach
This is a simple JavaScript game built using Test Driven Development (TDD) approach with Jest framework. It means that the game was developed by writing tests first and then implementing the code to pass the tests. Every function was written using Red-Green-Refactor cycle where we first write a test that fails, then we write the enaugh code to make the test pass and finally we refactor/optimising the code to make it more readable and maintainable.

## Environment setup
To run this game locally you need to have:
- [Node.js](https://nodejs.org/en/) - JavaScript runtime environment
- [npm](https://www.npmjs.com/) - package manager for JavaScript
- [jest](https://jestjs.io/) - JavaScript testing framework

Steps to set up the environment for new project:
1. Create a new directory for the project
2. Initialise npm in the project directory
- ``` npm init ```
All parameters can be left as default except for the test command. It should be set to: ``` jest ```
3. Install jest testing framework
- ``` npm install --save-dev jest ```
4. Install JSDOM environment allowing Jest to simulate a browser environment for testing purposes.
- ``` npm install -D jest-environment-jsdom ```

_To run the tests_:
- ``` npm test ```


### Credits
This game was built as part of the [Code Institute](https://codeinstitute.net/) Full Stack Software Developer course.