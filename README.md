# Sass

1: Used link: https://sass-lang.com/install to install 
2: https://github.com/sass/dart-sass/releases/tag/1.50.0 - installed dart sas in C:\program files x86\sass\dartsass
3: Added a variable under advanced system setting > variables > system variables (Path) > added the new dart sass variable
4: CMD checked verification of dart (sass --version)
5: in PHPstorm added the watcher automatically
6: Used https://sass-lang.com/guide for the Exercises: 

Your mission is to rewrite the example.css to a scss file with the following changes:

Part 1
- Make one mixin for the 3 lines of the box-shadow styling.
- Make the general padding the same everywhere with one variable. (red=16px, blue=8px), the footer h6 should have double the padding of the other elements. Use "operations" to do this. Do NOT hardcode the padding inside your scss.
- Nest the styling rules of grouped elements, like the sections in the Article.
- Make use of extend to re-use the same CSS for the "success", "error" and "warning" messages.

Part 2 (optional)
- Add an option to your compilation to minify your stylesheet! Mine was below 1.6k, can you do better? Do you still remember the option to ls to make the filesize Human readable?

7: Minify the css with https://www.cleancss.com/css-minify/