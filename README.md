# 📚 Day 42 – Reading/Writing Streams of Bytes & Strings in Java

Welcome to Day 42 of your Java learning journey! Today we stepped into the **world of Java I/O** — the magic behind how Java reads and writes data from files.

---

## 🧠 What We Learned

### ✅ Key Topics:

* **Streams in Java**: What are streams? Why do we need them?
* **Byte Streams** – for handling binary data (`InputStream`, `OutputStream`)
* **Character Streams** – for handling text (`Reader`, `Writer`)
* **Buffered I/O** – performance-friendly wrappers like `BufferedReader`, `BufferedWriter`
* **Try-with-resources** – managing streams safely and automatically
* **Unit testing I/O code with JUnit 5**

---

### 💼 Real-Life Project: **Java Post Office** 📬

A fun simulation of a digital post office:

* **Send** a letter → Write string to file using `BufferedWriter`
* **Read** a letter → Read string using `BufferedReader`
* **Duplicate** a letter → Copy file using byte streams

You now understand **how to handle files**, both for **text** and **binary data**, the Java way.

---

## 🎥 Zoom Recording

📺 Watch the session again:
👉 [**Zoom Recording Link**](https://us06web.zoom.us/rec/share/osxLJVutBhTAvY30Wg3ZoXGbXJ3lbQXtLcnSTunX3kfs2WMFNmD0hIIWGSyol3ur.Ye9Q_BHGDoYS835m?startTime=1748243713000)

---

## 💻 Live Coding Demo

Check out the code we wrote together:
🧑‍💻 [**GitHub Repo – Java Postman Demo**](https://github.com/FW-Zalando-Java-Backend-Engineer/Java-Postman)

---

## 🧪 Exercises for Practice

1. Write a program to:

   * Save user input from the console into a file.
   * Read the same content back.
2. Copy an image file (JPG/PNG) using byte streams.

🔗 [**GitHub Exercises Repo:  Java Assignment — "Digital Time Capsule"**](https://github.com/FW-Zalando-Java-Backend-Engineer/Digital-Time-Capsule)

---

## 🔁 Recap Questions

* What’s the difference between `FileWriter` and `FileOutputStream`?
* When should you use a buffered stream?
* Why use `try-with-resources` in I/O?
* What happens if you forget to close a stream?

---

## 📚 References

* [Oracle Java I/O Tutorial](https://docs.oracle.com/javase/tutorial/essential/io/)
* [Java 8 I/O – Official Docs](https://docs.oracle.com/javase/8/docs/api/java/io/package-summary.html)
* [Java I/O Byte Stream Implementation](https://medium.com/@lavishj77/java-i-o-byte-stream-implementation-6acf5a9ec848)
* [Reading and Writing Binary Files](https://dev.java/learn/java-io/reading-writing/binary-files/)
* *Fun read:* Why you don’t copy a binary file with `FileWriter` (hint: it ends up like Java code 😆)


