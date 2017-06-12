# Word Counter Tech Test

### Overview
This is a word counter tech test written in JavaScript. The task was to write a JavaScript application that takes any given text file and outputs the following:

1. Individual words that appear and the number of times the word occurs in that file.
2. Whether the number of times each word occurs is a prime number.

#### Assumptions:
1. Punctuation and capitalisation can be ignored.
2. TDD is expected.

#### Final Result:

![Terminal screenshot](https://github.com/connie-reinholdsson/word_counter_tech_test/blob/readme-update/images/Screenshot%202017-06-12%2016.22.06.png)

### My approach
1. **User Stories**: Broke down problem into user stories.
2. **Mock-up**: Mock-up page of how I imagine the final product will look, (see image below).

![Mock-up](https://github.com/connie-reinholdsson/word_counter_tech_test/blob/readme-update/images/20170612_121153.jpg)

3. **Node.js vs Browser**: After conducting research and experimenting with both, I decided to use Node as it offers a simple solution to reading and loading files and allows me to easily experiment with syntax in the terminal.
4. **Testing**: Decided to use Jasmine for its simplicity and easiness to read and interpret the tests.

### Technologies
- JavaScript
- Node.js (v8.1.0)
- Jasmine (v.2.6.3)
- NPM (v5.0.3)

### Deployment instructions
1. ```git clone https://github.com/connie-reinholdsson/word_counter_tech_test.git```
2. Run ```cd word_counter_tech_test```
2. Run ```node src/wordCounter.js``` in terminal
3. To change text file, replace file in 'book.txt'.

### User Stories
```
As a user,
So that I can use the application,
I want to be able to feed the application a text file.
```
```
As a user,
So that I can use the application,
I want to be able to see a list of all the individual words that appear in the text file.
```
```
As a user,
So that I can use the application,
I want to be able to see the number of times each word appears in the text file.
```
```
As a user,
So that I can use the application,
I want to be able to see if that word is a prime number.
```
