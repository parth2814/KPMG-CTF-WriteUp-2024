# 2. Data Vault Duel

![Screenshot 2024-08-11 122022.png](2%20Data%20Vault%20Duel%2046c3a2d38ff14218a74f019cbe43b708/Screenshot_2024-08-11_122022.png)

- From the description, I can see that the bucket name is given, which is publicly accessible, but I don’t have the AWS account, so I am not able to use AWS-cli directly, so I searched for this and got this AWS flag from searching.

```bash
aws s3 ls s3://kpmg-ctf1 --no-sign-reques
```

- From this command, I got some info about the bucket, like the available files in it, and one of the files is `rituognriteuonhbiorentgbvhuitrhoirtsnbiuort.txt`.

![image.png](2%20Data%20Vault%20Duel%2046c3a2d38ff14218a74f019cbe43b708/image.png)

- but without credentials, I can’t access this, so again, I tried to google how I could access it, and I found that using `wget` or `curl`, we can directly access that S3 bucket.

```bash
curl -O https://kpmg-ctf1.s3.ap-south-1.amazonaws.com/rituognriteuonhbiorentgbvhuitrhoirtsnbiuort.txt
```

- Using this command, I can curl the flag directly. hehe Piece of Cake 🫠

![image.png](2%20Data%20Vault%20Duel%2046c3a2d38ff14218a74f019cbe43b708/image%201.png)