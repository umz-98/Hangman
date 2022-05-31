# Hangman

Code written for a traditional hangman game.

## Function/code

### function

- The game functions using the standard hangman rules. A word is presented with the '_' notation for each letter. The player is than expected to guess letters until they either 'die' due to using up their lifes or guess the word correctly. Currently the game provides for 5 lives and a selection  of 6 words. 

### Code

- The code makes use of object oriented programming and monitors the 'number of lives' and the 'number of letters' (see below). This monitoring is done to execute the game.

```python
"""for i in range (len(self.word)):
            if new_letter.lower() in self.word[i]:
                self.word_guessed[i] = new_letter
     if new_letter.lower() in self.word:
            print('correct!')
            self.num_letters -= 1
     else:
            print('not in the word mate')
            self.num_lives -= 1
     pass"""
```

### To improve

- To make the game more user friendly I hope to add stickman sketches so that it is exactly like a hangman game on paper. 
