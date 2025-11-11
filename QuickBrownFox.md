# Quick Brown Fox (Medium)
A pangram is a phrase that includes at least one occurence of each of the 26 letters, 'a'...'z'. An common example of a pangram is "The quick brown fox jumps over the lazy dog" (hence the name of this problem). 
<br></br>
Your mission? Recognize any pangrams that come through your program. If input comes through and the input is not a pangram, report what letters are missing. A letter occurs in the phrase if it occurs either as upper case or lower case.
<br></br>
Input starts with a line that contains an integer (N) that's >= 1 and <= 50. The next N lines are eac<b>h</b> <b>a</b> <b>s</b>ingle p<b>h</b>rase, po<b>s</b>sibly containing upper and low<b>e</b>r case le<b>t</b>ters, spaces, decimal digits and punctuation characters ‘.’, ‘,’, ‘?’, ‘!’, ‘’’ and ‘"’. Each phrase consists of at least one, but not more than 100 characters.

### Input
```
3
The quick brown fox jumps over the lazy dog.
ZYXW, vu TSR Ponm lkj ihgfd CBA.
.,?!'" 92384 abcde FGHIJ
```
### Output
```
pangram
missing eq
missing klmnopqrstuvwxyz
```
