# Expressway (Easy) 🟢
<img width="320" height="297" src="[https://github.com/JammerDEV-Es/HackTheBox-ReviewAndWriteup/blob/main/Expressway/images/Expressway.png]">

## Well, this machine didn't seem too complicated to me, to be honest.
You have to do the reconnaissance phase, including scanning the UDP ports (using `-sU` in `nmap`), and that's where you'll discover what you'll need to use. 

You can use either `hashcat` or `john`, whichever you prefer, but in my case, I used `hashcat` to decrypt the hash using a dictionary. After that, I had to establish an SSH connection with the machine, and you'll have to exploit a vulnerability in the machine.
