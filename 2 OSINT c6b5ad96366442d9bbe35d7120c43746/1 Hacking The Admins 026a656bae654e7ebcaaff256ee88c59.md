# 1. Hacking The Admins

![Screenshot 2024-08-11 121938.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_121938.png)

- From the text I guess that we have to search for the name `Raghava Sai Sarva` and I got a LinkedIn link:

![Screenshot 2024-08-11 122125.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_122125.png)

- There is a hash in the description it is a base64 hash:

**`TmV2ZXlgZ29ubmEgZ212ZSB5b3UgdXAKTmV2ZXlgZ29ubmEgbGVOlHlvdSBkb3duCk51dmVylGdvbm5hlHJ1 bmQ
gYW5klGRlc2VydCB5b3UKTmV2ZXlgZ29ubmEgbWFrZSB5b3UgY3J5Ck51dmVylGdvbm5hlHNheSBnb29kYnllCk51dmVylGdvbm5hlHRlbGwgYSBsaWUgYW5klGh 1 cnQgeW91 CgpodHRwczovBBhc3RlYmluLmNvbS9uWm1 ibkJRMyAtlG 1 lb3c=`**

- After decoding using CyberChef:

![Screenshot 2024-08-11 122141.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_122141.png)

- I got a Pastebin link, let go and see what is there in the link:

![Screenshot 2024-08-11 122210.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_122210.png)

- From Previous Pastebin I got LinkedIn link and text that tells me to check the discord of `eren_meow` account,

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image.png)

- Here we got a base58 hash:

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image%201.png)

- let's go to the link::

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image%202.png)

- It password Protected so check out the discord account mentioned previously `eren_meow`, then let check the discord:

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image%203.png)

- here we got an hash that is Base58:

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image%204.png)

- Then We open the pastebin using `meowsaurabh123!` password,

![Screenshot 2024-08-11 122922.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_122922.png)

- Here again we got a LinkedIn link and a brainfuck code:

![Screenshot 2024-08-11 122959.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_122959.png)

- In the LinkedIn they have given a `pastebin link`:

![image.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/image%205.png)

- I got the flag 🫡

![Screenshot 2024-08-11 123047.png](1%20Hacking%20The%20Admins%20026a656bae654e7ebcaaff256ee88c59/Screenshot_2024-08-11_123047.png)