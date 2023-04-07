# React tasks guideline

This instruction explains how to work with React tasks on Github

## Get the initial code
1. `Fork` the repository 
2. `Clone` the forked repo
3. Run `npm install` to install the dependencies
4. Create a branch for you solution (e.g. `git checkout -b develop`)

## Develop the solution
1. Run `npm start` to run a development server at `http://localhost:3000`
  (If you need to stop the server press `ctrl + c` in the terminal window)
    > You should open a new command line window for all the next commands
2. Write the code inside the `src/` folder following the style guides:
    - [HTML and CSS styleguide](https://mate-academy.github.io/style-guides/htmlcss.html)
    - [JS styleguide](https://github.com/mate-academy/style-guides/blob/master/javascript.md)
3. Open one more terminal and run tests with `npm test` to ensure your solutions is correct
4. Run `npm run lint` to check the code style and fix all the errors
5. `add`, `commit` and `push` all the recent changes
6. Run `npm run deploy` to publish your solution to Github pages

## Prepare for code review
1. Create a `Pull Request` (`PR`) from `the-forked-repo/develop` to `the-original-repo/master`
2. Put your Github username into the `DEMO LINK` (above the task description) and add it to the `PR` description

> In order to update the PR repeat the steps 2-5 from the `Develop the solution` section
