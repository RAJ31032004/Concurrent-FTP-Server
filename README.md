# 🌐 Concurrent FTP Server using Socket Programming

## 📌 Project Description

This project implements a Concurrent File Transfer Protocol (FTP) Server using TCP socket programming in C.  
The server is capable of handling multiple client requests simultaneously by creating a new process for each connected client using the fork() system call.

---

## 🎯 Aim

To implement a Concurrent FTP Server using process-based concurrency with the help of the fork() system call.

---

## ⚙️ Features

- Multi-client support
- Simultaneous file transfer
- Process-based concurrency
- TCP Socket Programming
- File transfer using client-server communication

---

## 🛠️ System Calls Used

- socket()
- bind()
- listen()
- accept()
- fork()
- open()
- read()
- write()
- close()
- stat()

---

## 🖥️ Technologies Used

- Programming Language: C
- Platform: Linux (Ubuntu)
- Concept: Socket Programming

---

## ▶️ Compile Commands

```bash
gcc server.c -o server
gcc client.c -o client
