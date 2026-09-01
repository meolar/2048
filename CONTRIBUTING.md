# Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request.

Please follow the guidelines to have a bigger chance of your contribution being merged.

## Contribution Guidelines

### How to make changes
 - To make changes:
   - Fork this repository. On your new repository, make a new branch and then make you changes there.
   - Open up a pull request that merges your new branch that you made changes on to the master branch. <!-- Add documentation on how to do this? -->
   - Be sure to keep the branch up to date with changes made on the `master` branch!
 `gh-pages` is different from master in that it contains sharing features, analytics and other things that have no direct bearing with the game. `master` is the "pure" version of the game.
 <!-- If you want to modify the CSS, please edit the SCSS files present in `style/`: `main.scss` and others. Don't edit the `main.css`, because it's supposed to be generated.  
 In order to compile your SCSS modifications, you need to use the `sass` gem (install it by running `gem install sass` once Ruby is installed).  
 To run SASS, simply use the following command:  
 `sass --unix-newlines --watch style/main.scss`  
 SASS will automatically recompile your css when changed.
 - `Rakefile` contains some tasks that help during development. Feel free to add useful tasks if needed.-->
 - Please use 2-space indentation when editing the JavaScript. A `.jshintrc` file is present, which will help your code to follow the guidelines if you install and run `jshint`.
 - If you have not tested your modification thoroughly, Please make a Draft Pull Request. Drafts cannot be merged until marked as ready for review, so it helps designate what is work-in-progress and what is not.

### Some changes might not be accepted
We have to be conservative with the core game. This means that some modifications won't be merged, or will have to be evaluated carefully before being merged:

- Undo/Redo Features -- This would make the game too easy.
- Save/Load -- Would also make the game too easy.

### Changes that are welcome
 - Bug fixes
 - Compatibility improvements
 - "Under the hood" enhancements
 - Small changes that don't have an impact on the core gameplay
 - Ability to change the grid size
 - Start-up menu to change the settings before the game starts (e.g. grid size, emergency purge allowance, etc.)
 - Overall points -- The amount of points ever collected.
