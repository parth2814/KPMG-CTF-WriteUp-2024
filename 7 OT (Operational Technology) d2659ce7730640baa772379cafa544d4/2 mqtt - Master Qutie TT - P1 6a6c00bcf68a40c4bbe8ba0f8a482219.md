# 2. mqtt - Master Qutie TT - P1

![Screenshot 2024-08-11 122010.png](2%20mqtt%20-%20Master%20Qutie%20TT%20-%20P1%206a6c00bcf68a40c4bbe8ba0f8a482219/Screenshot_2024-08-11_122010.png)

- As per the decryption given, we have to access the HVAC system and try to subscribe to all the subtopics.
- So first of all, I don’t know how to access the mqtt service, so I just did a Google search and got the treasure.
- [**`1883: Pentesting MQTT (Mosquitto)`**](https://book.hacktricks.xyz/network-services-pentesting/1883-pentesting-mqtt-mosquitto)
- From this, I know which tool to use and how to use it, so I use `Mosquito.`

```bash
apt-get install mosquitto mosquitto-clients # Install the tool
```

- From Blog, I used the -t option for subscribing to all the subtopics, and from that, I got the flag. 🕺

![Screenshot 2024-08-11 120824.png](2%20mqtt%20-%20Master%20Qutie%20TT%20-%20P1%206a6c00bcf68a40c4bbe8ba0f8a482219/Screenshot_2024-08-11_120824.png)