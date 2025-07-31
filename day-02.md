# 🌱 Day 2 of My DevOps 60-Day Challenge  
## 🔧 Linux – Commands, File System, Users & Permissions  
<img width="708" height="730" alt="Screenshot 2025-07-31 053731" src="https://github.com/user-attachments/assets/4df55bf6-d37a-4a92-9f3a-66a413cf9603" />

---

Today, I officially stepped into the world that powers nearly every server, cloud VM, and automation system — **Linux**.  
It felt less like typing commands and more like unlocking superpowers that let me talk directly to the machine. 🧠

---

### 📁 File System Mastery

- 🔹 Navigated like a native using `cd`, `pwd`, and `ls`
- 🔹 Understood key directories: `/`, `/etc`, `/home`, `/usr`, `/var`
- 🔹 Created & deleted files and folders with:
  - `touch`, `mkdir`, `rm`, `mv`, `cp`

> 💡 Now I know where everything lives — and more importantly, what not to touch 😅

---

### 👥 Users & Groups

- 🔹 Identified myself with `whoami`
- 🔹 Explored user/group IDs using `id`
- 🔹 Added users, switched between them, and managed group permissions
- 🔹 Created a group and added users via `groupadd` and `usermod`

> 🎯 Managing access is the **first line of defense** in any secure system.

---

### 🔐 Permissions & Ownership

- 🔹 Broke down the `rwx` (Read, Write, Execute) pattern
- 🔹 Used `chmod` to control file permissions
- 🔹 Used `chown` to change file ownership
- 🔹 Learned about the **Principle of Least Privilege**  
  (aka stop running everything as root 🙅)

---

### ⚙️ Bonus: My First Shell Script

```bash
# hello.sh
echo "wassup!"
