# - FROM SERVERS TO CONTAINERS

### 1.In the traditional method, everything runs directly on one operating system.
#### - Hardware
This is the physical machine
Example: CPU, RAM, hard disk, network card

#### - Operating System (OS)
A single OS is installed on the hardware
Example: Windows, Linux, macOS
This OS controls hardware and resources

📦 Applications (App 1, App 2)
Multiple applications are installed on the same OS

All apps:

Share the same OS

Share system libraries

Share hardware resources

<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/af2a1deb-ddbd-448c-ab1c-55d4226a4c10" />

⚠️ Problems with Traditional Method
Dependency conflict

App 1 may need Java 8

App 2 may need Java 11

Same OS → conflict happens ❌

Poor isolation

If App 1 crashes, it can affect App 2

Scalability issue

Hard to scale one app independently

Resource wastage

One app may consume too much CPU/RAM and affect others

📌 Real-life Example
Think of it like:

One kitchen (OS)

Multiple dishes (apps)

If one dish needs high flame, others may get spoiled 🔥🍲

🧠 Summary (Easy Line)
👉 In the traditional method, all applications run on one operating system, directly on hardware, which causes conflicts, low isolation, and scalability issues.

