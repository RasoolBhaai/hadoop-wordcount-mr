# hadoop-wordcount-mr
Java MapReduce WordCount Program on Hadoop

# WordCount - MapReduce in Java

This project demonstrates a simple **WordCount** job written in Java using **Hadoop MapReduce**.

## 📁 Project Structure

- `WordCount.java` – MapReduce logic
- `input/sample.txt` – Sample text file for testing
- `build/wordcount.jar` – (Optional) Pre-built JAR
- `run.sh` – Shell script to compile and run the job

## 🛠 How to Compile

```bash
hadoop com.sun.tools.javac.Main WordCount.java
jar cf wordcount.jar WordCount*.class


