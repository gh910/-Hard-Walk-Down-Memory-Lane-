# Arab Security Cyber Wargames-[Hard] Walk Down Memory Lane Write-up

We have a zip file and this file contains a file of type dmp format.


At first I tried to use the volatility tool but it failed and then I decided to check the header of the file but it was correct. 
After that considering the description of the challenge I decided to use the strings tool.

strings -a Microsoft.dmp | grep -i "ASCWG"

![Screenshot_2022-08-07_08-09-23](https://user-images.githubusercontent.com/80649768/183290698-9b17f234-105b-40be-9d3d-eb40b84c89e6.png)
