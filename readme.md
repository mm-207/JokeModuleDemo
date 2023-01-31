# About

This repository is a simple demonstration of how to construct a Javascript module for multiple projects. Our primary concern is encapsulation and separation of concerns, secondly documenting our work in the readme file, but also with tests. 

# Joke Telling module.

## Usage
```javascript
import Joke from "joke.mjs"

const joke = new Joke(/*Joke list as array or \n seperated list*/);
console.log(`The joke teller knows ${joke.numberOfJokes}`)
console.log(joke.tellAJoke());

```


