# Password Generator 🔑  

This repository contains a simple script that generates a random password.  

## Code in This Repo  
```python
import random  
import string  

length = int(input("Enter password length: "))  
characters = string.ascii_letters + string.digits + string.punctuation  
password = "".join(random.choice(characters) for _ in range(length))  

print(f"Generated password is: {password}")
