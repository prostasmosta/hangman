### Hangman game

This is a computer version of well-known guessing game.
Program thinks of a random word, and player tries to guess
it by suggesting letters within a certain number of
guesses.

### Usage

**Launch**
```
$ ruby main.rb
```
**Settings**

Open file _data/words.txt_ to change words.

All figures are located in _/figures_ directory, you
can change them as you like.

If you want to change number of errors which player can make,
open _lib/game.rb_ . Change the constant 
`TOTAL_ERRORS_ALLOWED = 7`
at 3rd string.

**Output**
```
Слово: Й О __
          _______
          |/
          |     ( )
          |     _|_
          |    / | \\
          |      |
          |
          |
          |
        __|________
        |         |

Ошибки (5): Ж, А, Т, С, Е
У вас осталось ошибок: 2

Введите следующую букву: 
```
