# Setting up ssh on pwn.college

## First run this command to get a public ssh key with your linked email
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## Then under profile -> ssh keys Upload the .pub file which gets created
```
cat example_name.pub
```
This pub file can be found in \users\account_name on Windows

Once saved.. Start a challenge in pwn.college

## To start the ssh session

``ssh -i example_name hacker@pwn.college"
Do not use the .pub which is the public key

If an error occurs -> for mac/linux use chmod to change permision and make it only visible to your account.
On windows right click on the private key ( no extension ). Properties -> Security -> Advanced -> Remove Everyone & Disable Inheritance if enabled
