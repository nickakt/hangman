# hangman
Game hangman is writen on RUBY. 

How to Run 

ruby main.rb


How to play 

The app "wishes" takes random word from /data/word and separates it to chars. A player should guess
a word by typing the letter which might contain the guessed word. The user has only 7 attempts to guess
the entire word. If the attempts are exceeded the user/player will be "hangup"

Example of game interface

The guessed word is 'КОРОВА' . The user has made to errors  and guessed 2 letters. 

Слово: К О __ О __ __
_______
|/
|     ( )
|      |
|
|
|
|
|
__|________
|         |

Ошибки (2): Х, У
У вас осталось ошибок: 5

Введите следующую букву:


The new words can be added to /data/word.txt
Please note that word MUST BE in the upper case 