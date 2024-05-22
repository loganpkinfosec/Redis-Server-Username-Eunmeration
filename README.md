# redis-user-enum
This tool is designed to assist penetration testers enumerate potential users on a target Linux system where a Redis-Server is present by utilizing Redis's change directory feature. 

# Example Usage
./Enum_Usernames_Redis.py -ip 192.168.1.33 -w /usr/share/wordlists/seclists/Usernames/xato-net-10-million-usernames.txt 

./Enum_Usernames_Redis.py -ip 192.168.1.33 -w /usr/share/wordlists/seclists/Usernames/xato-net-10-million-usernames.txt -p 8888

./Enum_Usernames_Redis.py -ip 192.168.1.33 -w /usr/share/wordlists/seclists/Usernames/xato-net-10-million-usernames.txt --password secretpass


