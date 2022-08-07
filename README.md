# -Hard-Walk-Down-Memory-Lane-
Description : 

We have a zip file and this file contains a dmp file
At first I tried to use the volatility tool but it failed and then I decided to check the header of the file but it was correct. After that I read the description of the challenge and thought of using strings.

strings -a | grep -i "ASCWG" 
