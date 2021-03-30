### Text-Analyzer

##### By Isaac Moreno & Noah Woodrum👨‍💻

[View Here](https://github.com/isaacrmoreno/text-analyzer )

### Description:

Created and tested test analyzer for lesson project.

### Set Up Instructions:

1. Clone this [repository](https://github.com/isaacrmoreno/text-analyzer.git) to your desktop.
2. Navigate to the top level of the directory.
3. Open Index.html in your browser.

### Bugs:

N/A

### Specs

Describe: wordCounter()

1. Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

 2. Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

 3. Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

 4. Test: "It should return 0 for a string that is only spaces."
Code: wordCounter("             ")
Expected Output: 0

5. Test: "It should not count numbers as words."
Code: wordCounter("hi there 77 19");
Expected Output: 2

Describe: numberOfOccurrencesInText()

6. Test: "It should return 0 occurrences of a word for an empty string."
Code:
const text = "";
const word = "red";
NumberOfOccurrencesInText(word, text);
Expected output: 0

7. Test: "It should return 1 occurrence of a word when the word and the text are the same."
Code: 
const text = "red";
const word = "red";
NumberOfOccurrencesInText(word,text);
Expected Output: 1

8. Test: "It should return 0 occurrences of a word when the word and the text are different."
Code:
const text = "red";
const word = "blue";
NumberOfOccurrencesInText(word, text);
Expected Output: 0

9. Test: "It should return the number of occurrences of a word."
Code:
const text = "red blue red red red green";
const word ="red";
NumberOfOccurrencesInText(word, text);
Expected Output: 4

Describe: numberOfOccurrencesInText()

10. Test: "It should return 0 occurrences of a word for an empty string."
Code:
const text = "";
const word = "red";
NumberOfOccurrencesInText(word, text);
Expected Output: 0

11. Test: "It should return a word match regardless of case."
Code: 
const text = "red RED Red green Green GREEN";
const word = "Red"
NumberOfOccurrencesInText(word, text);
Expected Output: 3 

12. Test: "It should return a word match regardless of punctuation."
Code:
const text = "Red! Red. I like red, don't you?";
const word = "red";
wordCounter(word, text);
Expected Output: 3

### Technologies Used:

1. VSCode
2. GitHub
3. Jquery

### Contact:

✉️ [Email](mailto:ipdxcreative@gmail.com) - Isaac Moreno
✉️ [Email](mailto:heymymomthinksimcool@gmail.com) - Noah Woodrum

### Licenses:

MIT &copy; 2021 Isaac Moreno & Noah Woodrum
