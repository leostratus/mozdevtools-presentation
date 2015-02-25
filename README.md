## Mozilla Developer Tools Slide Deck Generator

This is where the code for the Mozilla Developer Tools slide deck generator lives. _It's not finished yet_ and so it won't do very much for you.

You don't need to clone this repo to use the generator. Use `npm`. See instructions below.

## Intended Audience

Use this if:

- you expect to talk about many different developer tools features in a single talk
- you want automation (file watcher, build tasks etc.)
- you have a working knowledge of the command line
- you are familiar with Node.js
- you are at least vaguely familiar with a web development workflow

Don't use this if:

- any of the items in the previous section don't make sense to you
- you are looking for presentation materials for general Mozilla evangelism - instead [go here](http://github.com/codepo8/mozilla-presentation-templates) and clone that repo instead, because there are no general evangelism slides in here (yet?).

## Usage

Assuming you have [Node.js](http://nodejs.org), install `generator-mozdevtools-presentation`:
``bash
$ npm install -g generator-bespoke
``

Make a new directory and `cd` into it:
``bash
$ mkdir my-presentation
$ cd my-presentation
``

Scaffold a new presentation:
``bash
$ yo mozdevtools-presentation
``

## Presentation Workflow

All source files for the presentation reside in the `src` directory.

Start a local preview server:
``bash
$ grunt server
``

Compile and deploy to GitHub Pages, assuming a git repo with `origin` pointing to GitHub:
``bash
$ grunt deploy
``

To manually deploy elsewhere, compile all assets into the `public` directory:
``bash
$ grunt
``

## Contributing Slides

Look at [this repo](#) for an example of how your slides should be structured.

Don't inline styles.

Provide speaker notes in the <aside> tags.

## Contributing Code

Fork the repo, commit your changes in your own branch, submit a pull request.

Your pull request must have tests. 

## Origin Story

This generator is based off of Mark Dalgleish's  [generator-bespoke](http://github.com/markdalgleish/generator-bespoke).

## License


=====

MIT
