# 2010_LSU_PT_Group_Project

The name of this project is Escape Room.

You enter the escape room using SSH.
Username: Guest
Remote IP: 192.168.56.XXX
Password: Guest

Once inside the shell, there will be a binary file.
Running the binary will prompt the user to choose one of three doors.
Each door has several clues that leads to one of three escape keys.
After finding the escape key, the user will be brought back to the original location and prompted to choose another door.
The user will have to find all three escape keys to escape the room and Capture the Flag.

The first door will consist mainly of linux command line tools to find the username.
The second door will consist of using password cracking tools and python to find the password.
The third door will consist of wireshark and searching pcap files to locate the IP address escape key.

Privilege escalation will be sprinkled in various locations.

Once all three cluse are found, the user will be allowed to run a new binary file that will prompt him to input the three keys to find the flag and escape the room.

After the user escapes, a program will run that will scramble the escape keys so the same credentials cannot be reused to escape the room the same way.
TG
