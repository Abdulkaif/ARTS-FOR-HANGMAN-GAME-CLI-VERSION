# Hangman Game

This is a simple Hangman game implemented in Python. The game displays a series of dashes representing a word to be guessed, and the player must guess individual letters to uncover the word before running out of attempts.


### Game Logo

The game logo is displayed as follows:

_                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                    |___/

### Game Over Art

In case the player loses the game, the following game over art is displayed:

┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
███▀▀▀██┼███▀▀▀███┼███▀█▄█▀███┼██▀▀▀
██┼┼┼┼██┼██┼┼┼┼┼██┼██┼┼┼█┼┼┼██┼██┼┼┼
██┼┼┼▄▄▄┼██▄▄▄▄▄██┼██┼┼┼▀┼┼┼██┼██▀▀▀
██┼┼┼┼██┼██┼┼┼┼┼██┼██┼┼┼┼┼┼┼██┼██┼┼┼
███▄▄▄██┼██┼┼┼┼┼██┼██┼┼┼┼┼┼┼██┼██▄▄▄
┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
███▀▀▀███┼▀███┼┼██▀┼██▀▀▀┼██▀▀▀▀██▄┼
██┼┼┼┼┼██┼┼┼██┼┼██┼┼██┼┼┼┼██┼┼┼┼┼██┼
██┼┼┼┼┼██┼┼┼██┼┼██┼┼██▀▀▀┼██▄▄▄▄▄▀▀┼
██┼┼┼┼┼██┼┼┼██┼┼█▀┼┼██┼┼┼┼██┼┼┼┼┼██┼
███▄▄▄███┼┼┼─▀█▀┼┼─┼██▄▄▄┼██┼┼┼┼┼██▄


### Stages of the Hangman

The stages of the Hangman are displayed as ASCII art and represent the progression of the game as incorrect guesses are made. The stages are as follows:

**1**

+---+
  |   |
      |
      |
      |
      |
=========



**2**

  +---+
  |   |
  O   |
      |
      |
      |
=========


**3**

  +---+
  |   |
  O   |
  |   |
      |
      |
=========


**4**

  +---+
  |   |
  O   |
 /|   |
      |
      |
=========


**5**

  +---+
  |   |
  O   |
 /|\  |
      |
      |
=========


**6**

  +---+
  |   |
  O   |
 /|\  |
 /    |
      |
=========

**7**

```
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
```

### Trophy Art

Upon successfully guessing the word, the following trophy art is displayed:

```
              .-=========-.
              \'-=======-'/
              _|   .=.   |_
             ((|  {{1}}  |))
              \|   /|\   |/
               \__ '`' __/
                 _`) (`_
               _/_______\_
              /___________\

```

Feel free to use and modify the code as you like! Have fun playing Hangman!







