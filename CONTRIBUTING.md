# Contributing
Changes and improvements are more than welcome! Feel free to fork and open a pull request.

Please follow the house rules to have a bigger chance of your contribution being merged.

## House rules

### How to make changes
 - To make changes, create a new branch based on `master` (do not create one from `gh-pages` unless strictly necessary) and make them there, then create a Pull Request to master.  
 `gh-pages` is different from master in that it contains sharing features, analytics and other things that have no direct bearing with the game. `master` is the "pure" version of the game.
 - If you want to modify the CSS, please edit the SCSS files present in `style/`: `main.scss` and others. Don't edit the `main.css`, because it's supposed to be generated.  
 In order to compile your SCSS modifications, you need to use the `sass` gem (install it by running `gem install sass` once Ruby is installed).  
 To run SASS, simply use the following command:  
 `sass --unix-newlines --watch style/main.scss`  
 SASS will automatically recompile your css when changed.
 - `Rakefile` contains some tasks that help during development. Feel free to add useful tasks if needed.
 - Please use 2-space indentation when editing the JavaScript. A `.jshintrc` file is present, which will help your code to follow the guidelines if you install and run `jshint`.
 - Please test your modification thoroughly before submitting your Pull Request.

### Some changes might not be accepted
We have to be conservative with the core game. This means that some modifications won't be merged, or will have to be evaluated carefully before being merged:

### A sort of wishlist
These features would be nice to have in the game.

 - Undo/redo features
 - Save/reload features
 - Changes to the grid size
 - Start-up menu to change the settings before the game starts (e.g. grid size, emergency purge allowance, etc.)
 - Overall points (the amount of points ever collected)
 - Some special features could only be available if the player has collected enough score. Each feature requires a certain amount of points to be 'paid'.

### Changes that are welcome
 - Bug fixes
 - Compatibility improvements
 - "Under the hood" enhancements
 - Small changes that don't have an impact on the core gameplay
