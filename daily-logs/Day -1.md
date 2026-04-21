# 📅 Daily Log — 2026-04-21

> **Day #:**  Day 1
> **Focus Area:** Networking
> **Time Spent:** 2 hrs

---

## 🎯 Today's Goals

- [TCP/IP] Goal 1
- [Linux and Windows fundamentals ] Goal 2

---

## 📖 What I Learned

### Topic 1: Port fast

Port fast is a STP(spanning tree protocol) toolkit used to connect switch port with end host immediately and establish forwarding state 
without delay.Delay refers to learing and lisiting state port has to go through before going to forwarding state

**Key Points:**
-Portfast has to be enabled only for port connected to end host not switches,routers etc.
-Portfast can only be used for access ports
-In some cases port fast is enabled for trunk ports
### Topic 2: Linux and windows fundamentals

Linux is considerably much more lightweight and you'd be surprised to know that there's a good chance you've used Linux in some form or another every day! Linux powers things such as:

Websites that you visit
Car entertainment/control panels
Point of Sale (PoS) systems such as checkout tills and registers in shops
Critical infrastructures such as traffic light controllers or industrial senors

**Key Points:**
1.echo:Output any text that we provide
2.whoami:Find out what user we're currently logged in as!
3.ls: files listing
4.cd:change directory
5:cat:concatenate or to display file content
6.pwd:print working directory
7.find:find the file  or search with specific extenstion
8.grep:search the content of files for specific values
9.&:This operator allows you to run commands in the background of your terminal.
10.&&:This operator allows you to combine multiple commands together in one line of your terminal.
11.>:This operator is a redirector - meaning that we can take the output from a command (such as using cat to output a file) and direct it elsewhere.
12.>>:This operator does the same function of the > operator but appends the output rather than replacing (meaning nothing is overwritten).


---

## 💻 Commands / Code Practiced
Packet tracer commands:

1.spanning-tree portfast - to enable portfast for a specific interface
2.spanning-tree portfast default - to enable portfast for all interfaces by default
3.spanning-tree portfast trunk - to enable port fast for trunk ports


Linux commands:

1. echo "Hello Friend!"

2.whoami

3.ls

4.cat todo.txt

5.pwd

6. find -name passwords.txt or  find -name *.txt

7. grep "81.143.211.90" access.log

8.grep -R "PRETTY_NAME" /etc/

9.echo hey > welcome

10.echo hello >> welcome

## 🧩 CTF / Lab Practice

**Platform:** TryHackMe
**Room/Challenge:** [Linux fundamentals part1]
**Difficulty:** Easy


## 🔍 New Tools / Concepts Encountered

1.CCNA 
 Tool used : packet tracer

2. Linux
 Tool used: Ubuntu



---

## 🔗 Resources Used Today

- [CCNA -portfast](Jermey's IT lab)
- [Linux fundamentals](https://tryhackme.com/room/linuxfundamentalspart1)

---


*Keep going. Consistency beats intensity. 💪*