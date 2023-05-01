Download Link: https://assignmentchef.com/product/solved-c-programming-language-project-5-the-word-hunter-game
<br>
The word hunter game typically consists of scrambled letters in a grid in which player seeks for hidden meaningful words. Hidden words are placed vertically, horizontally or diagonally. They may overlap but cannot be in zigzag form or wrap around. Your task is to create a word hunter puzzle and let the player play the game.




This is a 6×6 puzzle. There are 4 words hidden in this puzzle. That are:

<ul>

 <li>“hello” [4,0] &amp; [4,4] “world” [1,0] &amp; [5,4]</li>

 <li>“great” [0,0] &amp; [0,4]</li>

 <li>“random” [5,5] &amp; [0,5]</li>

</ul>




<strong>Puzzle Map: </strong>            Puzzle map is a 15×15 grid where each cell contains a character. To build a puzzle map, you must do the followings:

<ol>

 <li>Fill the whole map with randomly assigned characters. To do so, use a function that simply returns a random character without taking any input.</li>

</ol>




<ol start="2">

 <li>Words and their locations are stored in a file called</li>

</ol>




“word_hunter.dat”. The given piece of code reads the file and stores the words in a pointer array called “dict”. Coordinates of each word is also stored in an array called “coordinates”. Size of coordinates is 15×4 which are starting [x1, y1] and ending positions [x2, y2] of a word. You must place the words in dictionary on puzzle based on coordinates.




<strong>Gameplay: </strong>At the beginning of the game, puzzle is printed on the screen. All characters are lowercase. Then, program asks for a word and a coordinate (r=row, c=column). The coordinate can be either the beginning or the end of a word. Thus, program must search for all 8 directions (e.g., north, north-east, east, south-east etc.) as soon as player enters a guess (word). If guess of player is true, corresponding word on map must be converted to uppercase. Otherwise, there is no change on the map.




<strong>Termination Conditions:</strong> <strong> </strong>

<ol>

 <li>Player finds all the words in the puzzle. 2. Player types “exit game”.</li>

</ol>










Page <strong>1</strong> of <strong>2 </strong>













Page <strong>2</strong> of <strong>2 </strong>