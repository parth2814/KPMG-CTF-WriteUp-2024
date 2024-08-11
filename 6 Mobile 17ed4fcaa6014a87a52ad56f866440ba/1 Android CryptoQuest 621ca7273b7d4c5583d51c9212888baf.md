# 1. Android CryptoQuest

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/Screenshot_2024-08-11_122111.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/Screenshot_2024-08-11_122111.png)

- From the description, we got the apk file `mobilechall1.apk`.
- After decompiling the file with [`jadx-gui`](https://github.com/skylot/jadx) software for Windows,.
- After digging around in the decompiled classes and Java files, I found an example. `example.ctfchall` package which contains the class files of the decompiled code, and from this directory, i got the `MainActivity` file, which contains the `half-flag` in encoded format.

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image.png)

- After decoding this base85-encoded string, I got to know that this flag was pointing out something, which is `AndroidManifest.xml` file,

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%201.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%201.png)

- Then check out the `AndroidManifest.xml` file and hurray i got the another part of flag then i decode it with base64 scheme and assemble the flag,

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%202.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%202.png)

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%203.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%203.png)

- Assembling the Flag,

![1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%204.png](1%20Android%20CryptoQuest%20621ca7273b7d4c5583d51c9212888baf/image%204.png)