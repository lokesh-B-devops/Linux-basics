Day 03 – Linux Permissions & Ownership

🎯 Objective

Understand Linux file permissions and access control — a core DevOps skill.

---

🔍 Viewing File Permissions

ls -l

Example output:

-rw-r--r-- 1 user group file.txt

Explanation:

- Owner → rw-
- Group → r--
- Others → r--

---

🔐 Permission Symbols

Symbol| Meaning
r| read
w| write
x| execute

---

🔢 Permission Numbers

Number| Permission
4| read
2| write
1| execute

Examples:

- 7 → rwx
- 6 → rw-
- 5 → r-x
- 4 → r--

---

🛠 chmod Command

Add execute permission:

chmod +x script.sh

Numeric method:

chmod 755 script.sh

Meaning:

- Owner → rwx
- Group → r-x
- Others → r-x

---

🧪 Practice Commands

mkdir day3
cd day3
touch app.sh
chmod 744 app.sh
ls -l

---

🌐 DevOps Use Case

- Securing shell scripts
- Protecting SSH private keys
- Managing access on Linux servers
- Preventing unauthorized execution

---

✅ Day 03 Completed
