# Lab 6 : Username enumeration via account lock

<img width="2177" height="1157" alt="Screenshot 2026-09-14 193842" src="https://github.com/user-attachments/assets/15e8eb26-d14a-4085-b578-0537af807791" />
<br>
<br>
<br>

**In short, the lab is about guessing passwords, but if you enter more than three incorrect passwords, you will be blocked , We have the correct username for Carlos, and we want to compromise his account by guessing his password ,Therefore, we will use a valid username and password to help us with this. We will log in with the first account, then guess the password of the second account**

<br>
<br>
<br>

<img width="2587" height="1143" alt="Screenshot 2026-09-15 072503" src="https://github.com/user-attachments/assets/c0aef780-a826-4e13-bb74-5b15ddefabc2" />

<br>
<br>
<br>

**We will use the Intruder tool, specifically the Pitchfork attack, to enter a correct username and password, followed by the correct username and an incorrect password, until we find the correct one. PortSwigger has provided the passwords we will use for this attack, and one of them is the correct password. You can find them on the lab page under Candidate passwords**
<br>

**If you have no idea what the Intruder tool is or what the difference is between a Pitchfork attack and the other attack types, you can go here:**
https://portswigger.net/burp/documentation/desktop/tools/intruder/getting-started?utm_source=chatgpt.com

<br>
<br>
<br>

 <img width="3289" height="685" alt="Screenshot 2026-09-15 070006" src="https://github.com/user-attachments/assets/1387bcf6-a542-4fd9-916a-1e3006a6a7ab" />
 
<br>
<br>
<br>

**And there we have it — we found the correct password**


 
<br>
<br>
<br>

<img width="2988" height="506" alt="Screenshot 2026-09-15 070030" src="https://github.com/user-attachments/assets/8486c3b0-401f-4a9a-b339-3b33b6a7c10a" />


