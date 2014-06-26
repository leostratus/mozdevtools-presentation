Mozilla Developer Tools Slide Deck Generator
========================

This is where the code for the Mozilla Developer Tools slide deck generator lives.



Usage
=====

You don't need to clone this repo to use the generator. Only clone this repo if you want to contribute code to the project. Use these instructions to use the generator:

1. Make sure you have  Node.js and Node Package Manager (NPM) installed. Make sure your NPM version if >= 1.2.10. You can check your NPM version by running `npm -v` from the command line.

2. Run `npm install -g yo`

3. `yo mozdevtools-presentation `

4. Edit index.jade and style.styl to your heart's content.

5. `grunt server` is your friend.

6. Something else will go here as this evolves.

Contributing Slides
=====

Look at [this repo](#) for an example of how your slides should be structured.

Don't inline styles.

Don't inline JS with the expectation it will execute. Put that stuff in a CodePen or JSFiddle.

Provide speaker notes in the <aside> tags or else all bets are off for people representing that feature well.

Contributing Code
=====

There should be tests.

Fork the repo, commit your changes in your own branch, submit a pull request.
