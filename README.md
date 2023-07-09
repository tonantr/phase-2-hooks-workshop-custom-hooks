# Custom Hooks Workshop

## Learning Goals

- Understand the benefits of creating custom hooks
- Create custom hooks

## Introduction

This workshop is designed to walk you through a series of short exercises led by
an instructor where you'll be introduced to some new concepts, experiment with
code, and go over a solution. The setup for this workshop is different from a
typical lab, so make sure to read all the steps below before getting started!

## Workshop Videos

This series of videos walks through the setup for each exercise, as well as
going through a solution. Check out these videos if you're working on this
workshop outside of a lecture setting:

- [Workshop Playlist](https://www.youtube.com/watch?v=92MdajVNToM&list=PLc6AmvC5ZybzzDIuqsc7jDvDQEw8DgOjn)

You can view the solution code for this playlist on the `solution` branch.

## Setup

- Fork and clone this repo
- Run `npm install` in the repo directory
- Run `npm start` to run the project in the browser
- In another terminal, run `npm test` to run the tests for all exercises

In the tab that is running tests, you can press the `p` key to select a specific
test file to run. For example, hitting `p` and then typing `01.js` will run the
first test.

**NOTE**: if you get the following error when running `npm start` or `npm test`:

```text
Module not found: Error: Can't resolve '@styled-icons/heroicons-outline/ExternalLink'
```

In VS Code, navigate to the following file in the `node_modules` folder:

```text
node_modules/@ihollander/workshop-app/dist/components/sandbox.js
```

Then comment out the following line of code (line 22):

```js
var _ExternalLink = require("@styled-icons/heroicons-outline/ExternalLink");
```

## Instructions

The `src` directory has two folders: one for the `solution` code, and one for
the exercises. You'll be working in the `exercise` folder...

- `src/exercise/01.js`: Exercise (write your code here)
- `src/exercise/01.md`: Deliverables and helpful notes
- `src/__tests__/01.js`: Exercise test
- `src/__tests__/01.extra-1.js`: Test for extra credit exercise
- `src/solution/01.js`: Solution code (check your work, or look for a hint if
  you're stuck)
- `src/solution/01.extra-1.js`: Solution code for extra credit exercise

Each deliverable in the `exercise` folder has comments to guide your work!

There are some emoji to guide you in the exercises:

- ✅ Instructions where to write your code
- 👀 A hint on what syntax to use/what code to write
- 📃 Helpful documentation

> All credit to [Kent C Dodds](https://kentcdodds.com/) for the emoji guide
> idea, and general inspiration for this workshop format!

When running the workshop app in the browser, you can see the readme for each
exercise alongside a sandbox where you can view your exercise code to see if it
works. You can also open up your exercise code in a new browser tab to view the
exercise alone, and more easily see what's happening in the React Dev Tools.

You can also view working examples of the code in the browser by clicking the
solution tab.

Some exercises have bonus challenges to do for extra credit, so if you finish
early, give them a shot! Or save them for later when you want to revisit these
exercises.
