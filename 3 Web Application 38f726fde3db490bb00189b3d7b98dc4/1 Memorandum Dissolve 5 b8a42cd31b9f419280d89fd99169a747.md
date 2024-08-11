# 1. Memorandum Dissolve 5

![Screenshot 2024-08-11 122059.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_122059.png)

- In this Challenge I got an login page:

![Screenshot 2024-08-11 121108.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_121108.png)

- As I first checked the source code of the page(which i think is a best practice), Here, they have provided the test username and password

![Screenshot 2024-08-11 121158.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_121108%201.png)

- after logging in, I got a Welcome page, here I opened the inspect tool, for checking if there is any cookie is being used and i got the session cookie

![Screenshot 2024-08-11 121212.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_121212.png)

- The session looked like it was an md5 hash so i tried to crack it using online decoder([https://md5hashing.net/hash/md5/2cb42f8734ea607eefed3b70af13bbd3](https://md5hashing.net/hash/md5/2cb42f8734ea607eefed3b70af13bbd3)):
- MD5 hash:
    
     `test → 098f6bcd4621 d373cade4e832627b4f6`
    
- As I suspected, the session key is the username so i tried using admin md5 hash as a session key
- MD5 hash:
    
    `admin → 21232f297a57a5a743894aee4a801fc3`
    

![Screenshot 2024-08-11 121457.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_121457.png)

![Screenshot 2024-08-11 121506.png](1%20Memorandum%20Dissolve%205%20b8a42cd31b9f419280d89fd99169a747/Screenshot_2024-08-11_121506.png)

And we got the Flag. 🫡