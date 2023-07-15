# 1. Exploring Website Information and Generating Wordlist:

- During the process of exploring a website, we discovered the presence of user information.

![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/6dd20bda-c7bb-4c52-bdb9-afcebefcb6de)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/611b278c-e6bc-450c-a215-3d4d0774a99f)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/370b18a8-196d-4dff-bf14-918d73381b0c)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/7471ec01-b4bc-409a-9f55-594eb1aebf85)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/e10c3dca-450b-491d-9759-17c92437a02a)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/95028718-f80b-4a76-bcad-daa7e5ac7b4e)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/107b3a47-72b8-493b-9f2e-e4bd34bbd905)
![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/2a7bf9db-8124-46fe-b646-2c2c4dce0ec1)


- We compiled a list of usernames and saved them in a file for further analysis and use.

![image](https://github.com/singhx-hub/Active-Directory--Home-Lab-/assets/126919241/7dbdf2ff-7c89-4725-b6c6-f15ab3f136ee)

-  Use the ["usernamify"](https://github.com/singhx-hub/Usernamify) script to generate usernames by combining the first and last names from our user list and save the output in a text file

```python
└─$ ./usernamify.py web-users > userlist
jonathontaylor
taylorjonathon
jonathon.taylor
taylor.jonathon
taylorj
----snip------
tjonathon
j.taylor
t.jonathon
jonathon
```
- Navigate to the mail server in the browser using the UbuntuMail IP.
- Open Burp Suite and intercept the request using a proxy
- In Burp Suite's Intruder tool, initiate the attack by selecting the request and specifying the user and pass arguments for fuzzing. Add the generated username list to the user section and include common passwords like "summer2021!" and "fall2020!" as payload options. Configure the attack method as "Cluster Bomb" and launch the attack to test different combinations.
- Accomplished the task by successfully identifying the username "a.tarolli" along with the corresponding password "2021!"
- Log in to the mail server using the a.tarolli creds.
- 
