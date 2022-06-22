# Hangman
Game hangman is writen on RUBY. 



**About Game**


[WIKI](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))


**How to Run**

  
```
ruby main.rb
```

**How to play**


The app "wishes" takes random word from

```
/data/words.txt
```
and separates it to chars. A player should guess
a word by typing the letter which might contain the guessed word. The user has only 7 attempts to guess
the entire word. If the attempts are exceeded the user/player will be "hangup"

Example of game interface

The guessed word is 'КОРОВА' . The user has made to errors  and guessed 2 letters.

```
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
```

The new words can be added to

```
/data/word.txt
```
Please note that word MUST BE in the upper case 
