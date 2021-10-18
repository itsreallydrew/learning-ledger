## 10/15/2021

I learned how to make a game in Python. The game allowed the player to guess the 50 state capitols with a score tally running in the background and hints. I will add a copy of the game to this repo for reference.

## 10/16/2021

I edited one of my older projects from class. It is a stock tracker app that I customized. The API key was only working when I was testing on local host but not when I deployed the app. I realized I needed to add the key to the netlify platform and then I was able to get the deployed version to work. Also made sure to add redirects file as that caused a problem with my last application.

I also made some slight changes to make the project more responsive. I added a media query to hide the logo when the app was smaller than a certain size.

## 10/17/2021

I talked to some friends about coding in general and exchanged ideas.

## 10/18/2021

I completed the algorithm homework on stacks and queues and also did another solidity lesson.

The lesson involved writing tests for Smart Contracts on the Ethereum blockchain. The technology involved was Mocha/Chai (already familiar with from writing tests for APIs as well as examining the tests for our homework). Mocha is a test framework for Node.js that makes it easy to write asynchronous tests. Chai is BDD (Behavior-Driven-Development)/ TDD (Test-Driven-Development) library that is commonly paired with Mocha. The library contains the following styles: Should, Expect, and Assert. Truffle is a development environment and testing framework used for Ethereum and Ganache is a personal blockchain that allows for testing.

When writing tests in Truffle you can put an 'x' in front of the test i.e. xit("should skip this test", callback) -- and the test will be marked as pending when run.
