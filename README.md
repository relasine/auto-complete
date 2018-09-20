# Auto-Complete NPM Module

This repo contains an npm module for an auto-complete script. It was written using object-oriented programming and fits the basic structure of your typical prefix trie. It was originally created as a part of a Mod 2 project for the Front End Engineering program at the Turing School of Software and Design. My original repo for the project, entitled "Complete-Me" can be found [here](https://github.com/relasine/complete-me), and the specs for the project itself can be found on Turing's website [here](http://frontend.turing.io/projects/complete-me.html).

<img width="555" alt="screen shot 2018-09-20 at 7 42 57 am" src="https://user-images.githubusercontent.com/29719272/45822560-fa059e80-bca8-11e8-9493-0ecdfb868367.png">

To install this module:

``` npm install https://github.com/relasine/auto-complete.git ```

To create a new instance of the pre-trie:

``` const trie = new Trie(); ```

To add a word to the pre-trie:

``` trie.insert(newWord); ```

To populate the trie with an array of strings:

``` trie.populate(array); ```

To call the auto-complete function:

``` trie.suggest(string); ```

To increase a word's priority when calling suggest():

``` trie.select(word); ```

To delete a word from the pre-trie:

``` trie.delete(word); ```
