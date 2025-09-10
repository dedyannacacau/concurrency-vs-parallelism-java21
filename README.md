# Concurrency vs Parallelism in Java 21 🚀

This repository contains simple examples to demonstrate **Concurrency vs Parallelism in Java**, including the new **Virtual Threads (Project Loom)** introduced in **Java 21**.

## 📂 Project Structure

The project is based on **Maven** and includes three main classes:

- `FixedThreadPoolExample.java` → demonstrates **controlled concurrency** using `Executors.newFixedThreadPool()`.
- `ParallelStreamExample.java` → demonstrates **automatic parallelism** using `parallelStream()`.
- `VirtualThreadExample.java` → demonstrates **massive concurrency** using `Executors.newVirtualThreadPerTaskExecutor()` (Java 21 Virtual Threads).

## ⚙️ Prerequisites

- **Java 21** installed ([Download JDK 21](https://jdk.java.net/21/))  
- **Maven** installed  
- Recommended IDE: [IntelliJ IDEA](https://www.jetbrains.com/idea/) (but you can run it from any IDE or the terminal)  

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/concurrency-vs-parallelism-java21.git
cd concurrency-vs-parallelism-java21
```

Build the project:
```bash
git clone https://github.com/your-username/concurrency-vs-parallelism-java21.git
cd concurrency-vs-parallelism-java21
```

Run the examples:
```bash
mvn exec:java -Dexec.mainClass="org.example.FixedThreadPoolExample"
mvn exec:java -Dexec.mainClass="org.example.ParallelStreamExample"
mvn exec:java -Dexec.mainClass="org.example.VirtualThreadExample"
```

📖 Medium Post

This repository goes along with the article I wrote on Medium:
👉 [Concurrency vs Parallelism in Java: Exploring Virtual Threads in Java 21](https://medium.com/@dedyannacacau/concurrency-vs-parallelism-in-java-exploring-virtual-threads-in-java-21-a5b5a657a72a)

💡 Contributions

Feel free to open issues, submit PRs, or share ideas to expand this project.

Made with ☕ and 💻 by Dedyanna Cacau
