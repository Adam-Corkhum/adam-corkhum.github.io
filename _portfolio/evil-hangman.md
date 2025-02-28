---
title: "Evil Hangman"
excerpt: "A hangman game created in C that sneakily changes the secret word in order to make the game more difficult for the user.<br/>"
collection: portfolio
---

Evil Hangman was created as a part of a requirement for the Computing II course to create a hangman game in C that automatically changes the word to make the game more difficult.<br/>
## Breakdown <br/>
### 1. Dictionary Processing -
The program begins by reading words from a dictionary and separating them into dynamically resizing associative arrays based on the length of the word. The game will then select a family at random for the game.<br/>
### 2. Dynamic Word Manipulation -
The game now begins and the user guesses a letter. It will then split the word list into word families based on the positions of the letter. For example, if the user guesses 'a', it will create a word family of all letters without the letter a, all words with the letter 'a' in the first position, second position, etc. <br/>
### 3. AVL Tree Optimization -
To efficiently manage and sort words within each family, the program uses AVL tree, ensuring fast lookups and optimal balancing of potential word choices.

