Download Link: https://assignmentchef.com/product/solved-csci3110-lab3-object-oriented-programming
<br>
<strong>PURPOSE</strong>:

<ul>

 <li>learn to work with multiple classes</li>

 <li>review operator overloading</li>

 <li>review friends</li>

</ul>




<strong>Description: </strong>

Write a C++ program to play simple card game between you and the computer.  The game should proceed as follows.  The 52 cards in a deck of cards are shuffled and each player draws three cards from the top of the deck.  The remaining cards are placed in a pile face-down between the two players.  Players then select one of the three cards in hand and simultaneously place the chosen card face-up on the game table.  The player who placed the highest ranking card on the table retrieves both cards and sets the cards aside.  If both cards have the same rank, each player retrieves his/her card and sets the one card aside.  Then, each player selects the top card from the deck (and adds this card to his/her hand of cards.  Play continues until all cards have been played.  The winner is the player with the most points at the end of the game.




We will use a standard deck of 52 cards where there are thirteen cards from each of four suites including hearts, spades, diamonds and clubs.  The thirteen cards in order by rank include the 2-10 cards followed by face cards (Jack, Queen, King) and the Ace card.  Points are distributed as follows:  Ace=15, face cards=10, all other cards count as the numeric value indicates.




<strong>Requirements </strong>

<ul>

 <li>You are required to use C++ classes for this program. You should have a “deck” class, a “player” class and a “card” class. Header files for these classes are provided by the instructor. It is not necessary to modify the provided header files.</li>

</ul>




<ul>

 <li>Output for this program must clearly and neatly show that the program does work and that it works correctly. Your output should:

  <ul>

   <li>display the entire deck of cards at the beginning of the game, and after shuffle</li>

  </ul></li>

</ul>




<ul>

 <li>For each play, show the cards and score of each player before the play, the card each player plays, and the cards and score of each player after the play:</li>

</ul>




<ul>

 <li>Show the winner of the game.</li>

</ul>




A sample executable file is provided by the instructor. You can run the program and check the sample output formats.

<strong> </strong>

<strong>Hint: </strong>

Use the following statements to print suit symbols:

cout &lt;&lt; ((char)0x03); //print Heart symbol   cout &lt;&lt; ((char)0x04); //print Diamond symbol     cout &lt;&lt; ((char)0x05); //print Club symbol   cout &lt;&lt; ((char)0x06); //print Spade symbol




<strong>How to download assignment files: </strong>

Go to the URL: <a href="http://www.cs.mtsu.edu/~zdong/3110/public/OLA/OLA2.zip">http://www.cs.mtsu.edu/~zdong/3110/public/OLA/</a> and download the file OLA3.zip, which contains the following files:

<ul>

 <li>doc: this file</li>

 <li>doc: a rubric used to grade this assignment • OLA3.exe: an executable solution provided by the instructor.</li>

 <li>h: the header for the class Card.</li>

 <li>h: the header for the class Player. • Deck.h: the header for the class Deck.</li>

</ul>


