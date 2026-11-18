Lamport Logical Clock Simulator

📌 Project Description

A Java-based Lamport Logical Clock Simulator that demonstrates event ordering and message passing between three distributed processes (P1, P2, and P3). It assigns logical timestamps to events and maintains the correct ordering of events in a distributed system.

🎯 Objectives

- Understand Lamport Logical Clocks.
- Simulate three distributed processes.
- Demonstrate message passing.
- Assign logical timestamps to events.
- Maintain event ordering.

⚙️ Technologies Used

- Java
- JDK
- VS Code / Eclipse

🔄 Working Principle

1. Each process maintains its own logical clock.

2. The clock increments by 1 for every event.

3. When a message is received, the clock is updated using:
   
   "Clock = max(Local Clock, Received Timestamp) + 1"

🖥️ Processes

- Process P1
- Process P2
- Process P3

Communication flow:

"P1 → P2 → P3"

▶️ How to Run

1. Install Java JDK.

2. Save the program as "LamportClock.java".

3. Open the terminal.

4. Compile the program:
   
   "javac LamportClock.java"

5. Run the program:
   
   "java LamportClock"

📤 Sample Output

P1 Internal Event: 1
P1 Sends Message: 2
P2 Internal Event: 1
P2 Receives Message: 3
P2 Sends Message: 4
P3 Receives Message: 5
P3 Internal Event: 6

📊 Result

The simulator successfully demonstrates Lamport Logical Clock synchronization and logical event ordering among three distributed processes.

🌍 Applications

- Distributed databases
- Distributed operating systems
- Message-passing systems
- Event synchronization

👩‍💻 Student Details

- Name: Noorul Sakika
- Register Number: 814724104109
- Course Code: CS3551
- Course Name: Distributed Computing

📚 References

- Distributed Systems – George Coulouris
- Java Documentation
- Distributed Computing Course Materials

---

Project Type: Mini Project
Topic: Lamport Logical Clock Simulator
