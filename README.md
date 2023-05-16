# Introduction 📚

### What is this ?
This is a guide to disable the payment system from the PC version of the game "Genshin Impact", this game is know for using some shady method to make you spend more and more money this guide will stop this!

### Is this allowed *(EULA Compliant)* ?
Yes, this is allowed we are just blocking a server / url

### How does it work ?
It work by blocking the payment server *(sg-payment.cydf.hoyoverse.com & sg-payment-api.hoyoverse.com)* of Genshin Impact

# Guide❓

1. Open the start menu and type `notepad`, right click and press "Run as adminstrator" 

![image](https://github.com/CroissantDuNord/NoMoneyForGenshin/assets/79372025/f2d9211b-fcc9-4a88-953d-47fb258c07b9)

2. In notepad press `CTRL + O` and type `c:\Windows\System32\Drivers\etc\hosts` in the file name prompt, and click `Open`

![image](https://github.com/CroissantDuNord/NoMoneyForGenshin/assets/79372025/2777d243-804f-4853-a697-2237cb8fb743)

3. Add this at end of the file and press `CTRL + S` to save the file
```
127.0.0.1 sg-payment.cydf.hoyoverse.com
127.0.0.1 sg-payment-api.hoyoverse.com
```

*The final file should look like this:*
![image](https://github.com/CroissantDuNord/NoMoneyForGenshin/assets/79372025/ec5ed02b-3388-4b43-b7ff-073bbec6e874)

4. Its done!, Restart Genshin Impact, And the game will not allow you to buy anything for real money

![image](https://github.com/CroissantDuNord/NoMoneyForGenshin/assets/79372025/e6b6e514-5a31-48fd-8d82-2c1917bac175)

