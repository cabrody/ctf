## Musical Penguins - 45 (Forensics)
#### Writeup by cabrody
Created: 4-18-16

### Problem
This file is a complete mystery to me, I've never seen notes like these!

### Hint
Morgan Freeman and Kevin Spacey would have fun with this one!

## Answer
After researching the file type that the given file was, I downloaded the required program to view it properly
and was able to see that it was a piece of sheet music with only two alternating notes, in three-measure segments,
each separated by a full measure of rest.  I did some research on the hint, and found that Morgan Freeman and
Kevin Spacey were in three movies together, but by far the most popular of the three was Se7en, so I did some research
on that movie and read about its plot.  Unfortunately, this research wasn’t very important to the problem.  After looking
more at the music, I realized that if each measure was a letter to a code, then the first letter would be “s” and the
third letter would be “t”, and I noticed that the notes within the first and third measures were different by one note,
meaning that it was a code that would probably be a sort of number system, and, realizing the hint was just the number 7,
converted each set of three measures into a three-digit number in base 7.  For each of the lower notes, that counted as
one added to the digit.  For example, if a measure read EECCCC, that would denote the number two.  After converting each
of these measures into a number in base 7, I converted each to base 10, and then to ASCII, giving me the flag.
 
 
### Flag

`sctf{1_u53d_t0_m4k3_mu51c_w1th_th15_4ll_th3_t1m3}`
