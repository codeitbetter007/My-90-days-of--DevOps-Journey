# Getting Hands-On with Linux

So far, we have explored what Linux is and how its architecture works.

To truly understand Linux, theory alone is not enough. You need a Linux system to experiment with, break things, fix them, and explore how everything works.

There are several ways to get access to a Linux environment. Choose the one that best fits your goal and system setup.

---

## Ways to Get a Linux System

### 1. Dual Boot (Linux + Windows on the Same Machine)

In this setup, Linux and Windows coexist on your system. When you power on your computer, you can choose which operating system to boot into.

This involves partitioning your disk and installing Linux alongside Windows.

**Best for:**
- Full system performance
- Deep system-level learning
- Long-term Linux usage

**Video Guide:**
https://youtu.be/UUh6v08UPlc?si=7RxUy1tHyyS4reoB

---

### 2. Launch a Cloud VM and Connect Using SSH

You can launch a virtual machine (VM) in the cloud and connect to it using SSH (Secure Shell). This method is commonly used in real-world DevOps and production environments.

#### Linux on AWS EC2

**Video Guide:**
https://youtu.be/NfnVflt1Jxw?si=JASS1QRudUjOUsoY

#### Linux on Google Cloud Platform (GCP)

**Video Guide:**
https://youtu.be/fO6ZDH-bxSY?si=3x0Fda67z-gXjyxw

**Best for:**
- DevOps practice
- Cloud infrastructure learning
- Real-world server environment experience

---

### 3. Virtual Machines (VirtualBox / VMware)

You can install virtualization software on your system and run Linux inside a virtual machine.

This does not require disk partitioning and is generally safer than dual booting.

#### VirtualBox

**Video Guide:**
https://youtu.be/JyZoo5CGnC0?si=M9Y-r2F2oa8sRtqj

#### VMware

**Video Guide:**
https://youtu.be/SgfrHKg81Qc?si=irlhcKXP7TRsnIlV

**Best for:**
- Safe experimentation
- Beginners
- Learning without modifying your main OS

---

### 4. Windows Subsystem for Linux (WSL)

WSL allows you to run a Linux environment directly inside Windows without using a traditional virtual machine.

It integrates well with development workflows and is lightweight compared to full virtualization.

**Video Guide:**
https://youtu.be/zZf4YH4WiZo?si=Kb5K0579Wn3mlmBl

**Best for:**
- Developers
- Quick setup
- Command-line practice

---

## What Remains the Same Across All Methods

No matter which method you choose, the core Linux concepts remain the same:

- File system structure
- Shell and commands
- Process management
- User and group permissions
- Networking fundamentals

The environment may differ, but the Linux fundamentals do not.

---

## Recommended Path

- If you want full hardware access → Dual Boot
- If you want industry-relevant cloud experience → Cloud VM
- If you want a safe learning environment → Virtual Machine
- If you want a quick and simple setup → WSL

Choose your setup, install Linux, and start exploring.
