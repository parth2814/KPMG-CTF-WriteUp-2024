# 1. Modulus bus Station

![Screenshot 2024-08-11 121959.png](1%20Modulus%20bus%20Station%203a79481419e1433fbb39e6e2e406ad91/Screenshot_2024-08-11_121959.png)

- As per decryption, I can understand that I have to use the Modbus client tool to connect with the protocol. After some searching, I found a tool named `modbus_cli`.

```bash
pip install modbus-cli
```

- After installing it, I saw the manual for its usage, and after a while, I knew how to use it and got some raw data bytes in hex.

![Screenshot 2024-08-11 121143.png](1%20Modulus%20bus%20Station%203a79481419e1433fbb39e6e2e406ad91/Screenshot_2024-08-11_121143.png)

![image.png](1%20Modulus%20bus%20Station%203a79481419e1433fbb39e6e2e406ad91/image.png)

- I cleaned up the data in these 3 steps:
    1. First, grep all the hex data and remove other stuff in a file.
    2. Then I convert each bytes hex to ASCII character equivalent.
    3. Then remove all the duplicate bytes from the data.
    4. Then combine all the data.

![image.png](1%20Modulus%20bus%20Station%203a79481419e1433fbb39e6e2e406ad91/image%201.png)

- Then i try to decode it from CyberChef and i got the flag, 🫠

![image.png](1%20Modulus%20bus%20Station%203a79481419e1433fbb39e6e2e406ad91/image%202.png)