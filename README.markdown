#1. Name
ntp\_monlist
#2. Author
Gert Burger < gert(at)sensepost(dot)com >
#3. License, version & release date
License : CC BY 2.5  
Version : v.1.0  
Release Date : 31/02/2010
#4. Description
Basic script to pull addresses from a NTP server using the monlist command. Can also output Maltego resultset.
#5. Usage
python ntp\_monlist.py target_server (then wait 7-10 seconds(With default timeout and tries))  
If you dont receive close to 600 addresses then either your connection is too slow or the target server is not busy/popular enough. The script can act as a local transform for Maltego by changing the OUTPUT\_FORMAT variable close to the top.  
You will need to set the speed/accuracy (results slider to the far right for all results).
#6. Requirements
Python
#7. Additional Resources 
Blog - http://www.sensepost.com/blog/4552.html

