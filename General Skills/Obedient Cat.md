# Obedient Cat - Write up
**Credit:** [picoCTF - Obedient Cat](https://play.picoctf.org/practice/challenge/147?page=1&search=obedient%20cat)
This is the first beginner for who want to learn HACK!!!:
<img width="518" height="403" alt="image" src="https://github.com/user-attachments/assets/56b3bf36-00bf-4749-8a29-7bef50e6743d" />

Hints:1.Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.

2.To get the file accessible in your shell,enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/a5683698ac318b47bd060cb786859f23/flag

3.$ man cat

---

## Description

it very simple to explain so,This will explain what the hints say:
you must know first command in picoCTF is "wget" it short for World Wide Web Get
it mean open-source utility that allows you to retrieve content from web servers via HTTP, HTTPS, and FTP protocols.

---

when you know This command you can try in Webshell but you don't know Webshell!!!

Ok,let's explain the Webshell easy to explain,In Linux we use kalilinux to use in cybersecurity in Kali use Terminal to write command. It same in picoCTF we use Webshell to write command.

This is symbol of Webshell:
<img width="95" height="63" alt="image" src="https://github.com/user-attachments/assets/abfe7fff-c308-4861-a648-0ea40ae56d31" />

---

In hints tell to wget https://mercury.picoctf.net/static/a5683698ac318b47bd060cb786859f23/flag

When you wget ,now see in Webshell wait you are beginner??

ok I will explain the command it "ls" it means used to list files.

---

Now you know "ls" ok let do write: ls

and now you see:<img width="26" height="13" alt="image" src="https://github.com/user-attachments/assets/0ce6a9bc-3a73-43c6-aa24-96e686db9552" />

Ok i will easy explain when you use ls it show the all file in folder.

---

when you know all in top next hint will show CTF i wish. T_T

You see in Hint 3: <img width="137" height="119" alt="image" src="https://github.com/user-attachments/assets/d01e46a2-1762-49dc-b236-f735f8bd59e4" />

man cat //??? what it mean,Let's explain if i use common sense,I will write man cat in Webshell because it look like a command if you write it show

<img width="449" height="355" alt="image" src="https://github.com/user-attachments/assets/608ff875-ea81-4561-8de5-fa8d39b8fa1a" />

---

Let's me explain if you think like me you're halfway there because "man" it command yes but "cat" in lines it not a command so, first i will tell you means for"man"

"man" it means to display the user manual of any command that we can run on the terminal. **Terminal = Webshell**

and now see "cat" it mean concatenate.

---

Final, you got a file ,you know a command and means .Now use a common sense : It **read file**

write **cat flag** and now we got a CTF. Yeah!!

---

## Summary command

**wget** - open-source utility that allows you to retrieve content from web servers via HTTP, HTTPS, and FTP protocols.

**ls** - to list files.

**man** - display the user manual of any command that we can run on the terminal.

**cat** - concatenate.

---

Now it finish i hope you enjoy in CTF. Good luck and keep practice.❤️‍🔥❤️‍🔥
