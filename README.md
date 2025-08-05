# 💬 Java Chat Application (AWT + Sockets)

This is a basic two-way chat application using **Java Sockets** for networking and **AWT** for the graphical user interface. It demonstrates real-time communication between two users over TCP.

---

## ✨ Features

- Two-way chat (Server: Person1, Client: Person2)
- GUI built with Java AWT (TextArea, TextField, Button)
- TCP Socket communication
- Real-time message exchange using multithreading

---

## 🧰 Technologies Used

- Java AWT (GUI)
- Java Sockets (Networking)
- Java Threads

---

## 📦 Requirements

- Java JDK 8 or above
- Any Java IDE or terminal/command prompt
- Basic understanding of networking concepts

---

## 🚀 How to Run

### 1. Compile both files:

```
javac Person1.java
javac Person2.java
```

### 2. Start the Server (Person1):

```
java Person1
```

### 3. Start the Client (Person2) in a new terminal or different machine:

```
java Person2
```

> Ensure both programs run on the same network or use `localhost` for local testing.

---

## 📁 File Structure

```
📦 ChatApp/
├── Person1.java   # Acts as the server
├── Person2.java   # Acts as the client
└── README.md
```

---

## 🧑‍💻 Author

Developed by [Your Name]

---

## 📜 License

This project is licensed under the MIT License.
