# 🧪 C Programming Lab

## 📘 Experiment No: 2e
### 🔹
**Date:** 20/2/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
o write a C program to find the factorial of a given number using functions.
---

## 🧠 ALGORITHM
1.Get a input number from the user.
2.write a function to find the factorial of a number and call the function using the given number as argument.
---

## 💻 PROGRAM
```c
#include<stdio.h>
void fact(int);
void fact(int n1)
{
    long long int m=1;
    for(int i=1;i<=n1;i++)
    {
        m*=i;
    }
    printf("Factorial value is: %lld",m);
}
int main()
{
    int num;
    scanf("%d",&num);
    fact(num);
    
}
```
---

## 🖼️ OUTPUT SCREENSHOT
<img width="807" height="100" alt="image" src="https://github.com/user-attachments/assets/d5012e4b-e1ce-4834-b532-ec455f8bf277" />


---

## ✅ RESULT
Thus, the C program to find the ASCII value of a given character is executed successfully.
