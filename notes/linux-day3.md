# Linux Learning – Day 3
**Date:** 2025-11-12

**Goal:**
Practice managing file and directory permissions and ownership using `chmod` and `chown`.

---

## Commands Learned / Practiced
| Command | Description | Example |
|---------|------------|---------|
| `chmod` | Change file/directory permissions | `chmod 640 file.txt` |
| `ls -l` | List files with permissions, owner, group | `ls -l file.txt` |
| `ls -ld` | List directory with permissions, owner, group | `ls -ld folder/` |
| `chown` | Change ownership of file/folder | `chown $USER:$USER file.txt` |

---

## Practice Summary
- Created files and folders:

day3_permissions/testfile.txt
day3_permissions/share/group_note.txt
- Modified permissions using `chmod` and checked with `ls -l` and `ls -ld`.
- Learned numeric and symbolic permission notation.
- Practiced removing files safely using `rm` and `rmdir`.

---

## Reflection
- I’m more confident navigating and managing files in Linux.
- Next, I’ll explore users, groups, and sudo privileges (Day 4).

