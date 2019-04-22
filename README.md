# bruteforce-bootloader-unlock
A bot that try to bruteforcing my huawei phone's bootloader password.

## 2019-4-22
Using this code to bruteforcing Huawei bootloader is not practical, there are three factors that will causing this almost impossible to unlock the bootloader, here's the explanation:

1. The uncertainty of the combinations

   I've tried to get huawei's phone bootloader password combination and length from the internet, And most of the photos I got are censored. But they shared the same length of the key, it is a 16 letters key.
   
2. MATH!
   case 16 digit of 0-9
       possible combinations = 10^16
       time used for each attempt: 1 seconds (avg. included reboot time)
       attempts of after each reboot: 3
       worst case: (10^16 / 3) = 3.3333e15 seconds
   It almost impossible!
   
3. Your device might patched
   Acording to XDA, Huawei will patch it up and after that user can no more unlocking their bootloader. 
   
Wish you luck!

GC
