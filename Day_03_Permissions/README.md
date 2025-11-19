# Day 3 — Linux Permissions & Ownership

## Learning Objectives
- Learn about file permissions (read, write, execute)
- Understand permission categories: user, group, others
- Use chmod to modify permissions (symbolic and numeric)
- Change file ownership using chown and chgrp
- Understand why permissions are important for security

## Key Concepts
- Permission string example: -rwxr-xr--
  - user: rwx
  - group: r-x
  - others: r--
- Octal permissions:
  - 600: read/write for user only
  - 644: read/write for user, read for group and others
  - 700: full access for user only
  - 755: common for scripts
- Ownership:
  - Every file has a **user owner** and a **group owner**
  - Use `ls -l` to view owner and permissions

## Practice Summary
- Changed permissions on files and scripts
- Tested execution before and after changing execute bit
- Modified file ownership and group
