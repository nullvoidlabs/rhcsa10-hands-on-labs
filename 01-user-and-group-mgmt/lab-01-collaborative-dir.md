# **The Collaborative Directory Challenge**

**Strategy:** **Concrete Examples**

**Explanation:** This strategy fits the RHCSA preparation because abstract concepts like "special permission bits" are often difficult to grasp in isolation. By illustrating them with a **specific, real world scenario** (such as a departmental shared folder), the abstract rules become easier to understand and remember during the high-pressure environment of the exam.

*You need to set up a shared environment for a team of developers. Please provide the terminal commands to accomplish the following:*

1. **Create a group** named `dev-team`.
2. **Create a user** named `developer1` and add them to the `dev-team` as a **secondary group**[6][7].
3. **Create a directory** at `/projects/internal`.
4. **Set the group owner** of the directory to `dev-team`.
5. **Configure permissions** so that the owner (root) and the group (`dev-team`) have full access (read, write, execute), but **others have no access**.
6. **Apply a special permission** so that any new file created inside `/projects/internal` is automatically **group-owned by** **dev-team**.
7. **Apply a special permission** so that users can **only delete files they own**, even if they have write access to the directory.
