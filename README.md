# HTMLTagGuesser
App Inventor HTML Tag Guesser
===
About HTMLTagGuesser
---
Our original idea was to create an application that could challenge the user's knowledge about HTML tags. When we decided upon an app where you guess as many HTML tags as you can, we considered how to implement these ideas into App Inventor. Soon enough, we concluded that a text box would suffice, where you input a guess that the app reads and checks with a list of tags to see if the guess matches any HTML tag. We also wanted a counter that keeps track of the user's correct guesses, to add some measure of reward for correctly guessing a large number of tags. The primary challenge of this app was to read the contents of a text file containing all the HTML tags, transfer them to a list variable, and check if the guessed tag exists within the list. Functionally, in the final product, the app takes the guess, removes any "<" and ">" symbols, trims the guess, converts it to lowercase, and finally adds a "<" to the start and a ">" to the end. By doing this, we could accurately compare the guessed tag with the tags in the list that App Inventor reads from. There were a lot of things that could have gone wrong with this approach, and admittedly, a few things did. Making it all work the way we intended took some time. However, when testing the finished application, we noticed a slight flaw. The most recently inputted tags appeared at the bottom, rather than at the top. This problem was hardly difficult to fix, so it took only a few minutes to find the right place in the code to reverse the list of guessed tags that is written out. And with this fix, the app was finished and exported. You input a guess into a text box, click the "Guess" button, and if your answer is correct, the guess is removed from the list of remaining HTML tags and is added to your list of correctly guessed HTML tags.

Team
---

