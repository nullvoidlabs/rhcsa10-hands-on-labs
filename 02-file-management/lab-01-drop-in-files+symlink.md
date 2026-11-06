# Sudo Drop In Files & Symlink Removal Safety

**Strategy:** **Interleaving**

**Explanation:** Interleaving involves switching between distinct topics during a single study session rather than practicing one topic repeatedly. Combining **Sudo Privilege Configuration (** **/etc/sudoers.d/** **)** with **Symbolic Link Management** forces your brain to discriminate between user privilege rules and file system mechanics. On the RHCSA exam, questions are presented out of chapter order, so interleaving builds the cognitive flexibility required to execute commands accurately under exam conditions.

*Please provide the terminal commands and explanations for the following scenario:*

1. **Sudo Drod In Configuration:** You need to grant user `developer1` administrative permission to run `/usr/bin/systemctl restart httpd` and `/usr/bin/journalctl` without prompting for a password.
  * Write the exact command to safely create or edit a drop in file named `dev_access` inside `/etc/sudoers.d/`.
  * Write the exact rule line that should go inside `/etc/sudoers.d/dev_access`.
2. **Creating a Soft Link:** Create a symbolic link at `/var/www/app_link` that points to the target directory `/srv/app/data`.
3. **Safe Symlink Deletion & Syntax Error Check:** You are tasked with removing *only* the symbolic link `/var/www/app_link` without affecting any of the actual files inside `/srv/app/data`.
  * What is the safe command to remove the symbolic link?
  * **Crucial Exam Catch:** What specific syntax error (e.g., trailing punctuation or flags commonly added by shell auto completion) must you avoid, and what happens if that error is made?

