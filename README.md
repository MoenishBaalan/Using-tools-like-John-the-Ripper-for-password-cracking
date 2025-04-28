# Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
- Create an txt file
![image](https://github.com/user-attachments/assets/b6978c75-6128-4878-b569-da2fdeebef1f)


-  Create a Password-Protected ZIP File 
![image](https://github.com/user-attachments/assets/95bc302b-3926-4faf-bd4a-5a3633a4ca17)


### OR
```
zip -e secret.zip file.txt
```

- Open John-The-Ripper Tool
![image](https://github.com/user-attachments/assets/f99e8250-9e01-44f1-8dfc-76429d89e88f)

![image](https://github.com/user-attachments/assets/842af5b7-2787-4679-ba81-3f164cba9947)

  
- Generate Hash Using zip2john 
![image](https://github.com/user-attachments/assets/d874fc2f-d938-42ae-9124-a4f913f62162)


- cat hash.txt

![image](https://github.com/user-attachments/assets/d4716ece-53ba-425e-96b1-6a0f6d46c5cb)


![image](https://github.com/user-attachments/assets/41cd3e26-07c0-4d45-8e88-320a821d3c49)


## RESULT:
The password hashes were successfully cracked using John the Ripper.
