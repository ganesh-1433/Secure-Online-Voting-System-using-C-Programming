# 🗳️ Secure Online Voting System (C Programming)

## 📄 Abstract

In the contemporary digital era, technology continues to transform critical systems — including how we conduct elections. This project introduces a **Secure Online Voting System** built using **C programming**, which emphasizes the **security**, **integrity**, and **efficiency** of the voting process.

The system comprises **administrative and student panels**, each with distinct functionalities. Key features include **user authentication**, **candidate registration**, **secure voting**, and **result computation**. By focusing on vote confidentiality and administrative control, this solution ensures a reliable and transparent electoral platform.


## 🛠️ Tech Stack

* **Language**: C
* **Environment**: GCC / Turbo C++
* **File Handeling**: Standard C File I/O
* **Data Structures**: Structs and Array
* **OS**: Windows/Linux

## 🏗️ System Architecture

The system is divided into two main modules:

### 🔒 Administrative Panel

* 🔑 **Authentication**: Access secured with admin username & password.
* 🗂 **New Election Setup**: Define election year, branch code, voter count, and candidate count.
* 🧾 **Candidate Registration**: Assign unique candidate IDs and names.
* ❌ **Illegal Vote Management**: Delete votes by user ID if flagged as illegal.
* 🚫 **Ban Users**: Disable specific user IDs from voting.
* 📊 **Result Declaration**: Automatically calculate and display winning candidate & voting stats.

### 🎓 Student Panel

* 🪪 **User Authentication**: Voters log in with their unique user ID.
* ✅ **Validation & Authorization**:

  * Checks if the user is valid.
  * Verifies if the user already voted or is banned.
* 🗳️ **Voting Mechanism**: Securely cast votes from a list of candidates.
* 🤐 **Vote Confidentiality**: Votes are recorded with user IDs without revealing identities.
* 🚪 **Exit Option**: Voters can quit the process by entering `0`.


## ✨ Key Features

* 🔐 Secure admin and student login
* 🧾 Candidate registration and ID generation
* 🗳️ Cast votes securely and privately
* 🧹 Admin control to manage or remove illegal votes
* 📊 Automatic vote counting and result display
* 🔁 Reusability for multiple election sessions
* 💾 Data persistence using file handling


## ⚙️ How It Works

1. **Admin Login** → Access granted via password.
2. **Setup Election** → Configure year, branch, voter count, candidates.
3. **Register Candidates** → Assign candidate IDs and names.
4. **Student Login** → Voters authenticate with their unique ID.
5. **Vote Casting** → Vote is recorded securely and confidentially.
6. **Admin Result Panel** → Results are computed and shown with vote percentages.


## 🧩 Installation

### 📥 Requirements:

* C Compiler (GCC/Turbo C++)
* Code Editor (e.g., Code::Blocks, VS Code)
* Basic C knowledge

### 🧪 Steps to Run:

```bash
# Compile the C program
gcc voting_system.c -o voting

# Run the program
./voting
```

> Ensure all `.txt` or data files used in the project (if any) are in the same directory.


## 📊 Results

* ✅ Successfully implemented in an academic setting
* 🧑‍🎓 Verified by 100+ student users during testing
* 🔒 Demonstrated reliable vote confidentiality
* 👨‍💼 Admin functionalities ensure complete control of voting process
* 📈 Helps reinforce real-world C programming with a practical use case


## 🤝 Connect

📬 **Share your story** ([work.ganeshpawar03@gmail.com](mailto:work.ganeshpawar03@gmail.com)) if you're using this repo for your mini or course project. I’d love to know how this project helped you!


You Can Connect with on: 

🔗 [LinkedIn](https://www.linkedin.com/in/ganesh-pawar143)
💻 [GitHub](https://github.com/ganesh-1433)
