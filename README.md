# Rogerdell5
After trying to use myrburrows.com as a custom
domain, I give up.  So just making a change so
Rogerdell5 will re-deploy (I hope).

Unlike the old ones (Rogerdell6 or Rogerdell9to5)
Rogerdell5 is uppercase all the time.
So, script.js has differences with the others:
$ grep -i upper script.js
      if (elem.textContent.toUpperCase() === letter) {
    pressedKey = pressedKey.toUpperCase();

As well as just 5 grays
  var letterColor = ["gray", "gray", "gray", "gray", "gray"]
  and having "5" used 7 times for length of the word/guesses
  
