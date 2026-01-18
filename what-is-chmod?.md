# Here we have a brief explanation about what chomd is and works

The **`chmod`** command is used to **change file and directory permissions** in Linux OS.

---

##  Basic Concepts

- **Users involved**
  - `u` → user/owner
  - `g` → group
  - `o` → others
  - `a` → all

- **Types of permissions**
  - `r` → read
  - `w` → write
  - `x` → execute

- **Special bits**
  - `setuid` → runs with the owner’s privileges
  - `setgid` → runs with the group’s privileges
  - `sticky bit` → in directories, only the owner can delete

---

## ⚙️ Usage Modes

### 1. **Symbolic mode (more readable)**
Uses letters and operators:
- `+` → adds permission
- `-` → removes permission
- `=` → sets exacts permission

Examples:
```bash
chmod u+x file     # add execute for the owner
chmod g-w file     # remove write from the group
chmod o=r file     # others can only read

Were are some additional examples:
```bash
chmod u+x programa.sh
chmod g+r documento.txt
chmod a+r informe.pdf
