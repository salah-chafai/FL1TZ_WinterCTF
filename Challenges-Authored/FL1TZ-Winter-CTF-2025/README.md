# 🚩 FL1TZ-Winter-CTF-2025 🚩

This repository contains all the challenges I authored for the **FL1TZ-Winter-CTF-2025**, along with their solutions and writeups. The repository was made public after the CTF concluded.

---

## 📂 Repository Structure
```
FL1TZ-Winter-CTF-2025/
└── Pwn/
    ├── challenge-1/
    │   ├── description.md
    │   ├── attachments.zip
    │   ├── challenge
    │   ├── writeup
    │   └── Dockerfile
    ├── challenge-2/
    │   ├── description.md
    │   ├── attachments.zip
    │   ├── challenge
    │   ├── writeup
    │   └── Dockerfile
    └── ...
```
---

## 🧩 Challenges  
Each challenge is organized into its own directory, containing the following:
- **`description.md`**: A detailed description of the challenge.
- **`attachments.zip`**: Files provided to participants (e.g., binaries, source code, or other resources).
- **`challenge`**: The challenge binary, source code and flag.txt.
- **`writeup`**: Includes the solver.py script and a detailed solution walkthrough, when applicable.
- **`Dockerfile`**: A Dockerfile to replicate the challenge environment locally.

---

## 🚀 **Getting Started**
1. **Clone the Repository:**
   ```
   git clone https://github.com/salah-chafai/CTF-Compendium.git
   ```
2. **Navigate to a Challenge:**
   ```
   cd CTF-Compendium/Challenges-Authored/FL1TZ-Winter-CTF-2025/Pwn/challenge-1/
   ```
3. **Set Up the Environment:** 
   Build the Docker image:
   ```     
   docker build -t challenge-1 .
   ```
   Run the container:
   ```
   docker run -it --rm challenge-1
   ```
4. **Solve the Challenge:**  
   Use the provided description.md and attachments.zip to understand and solve the challenge.  
   Refer to writeup if you need help or want to verify your solution.

---

## 📜 License  
This repository is licensed under the MIT License. Feel free to use, modify, and distribute the challenges and writeups, but please attribute the original work to the author.
