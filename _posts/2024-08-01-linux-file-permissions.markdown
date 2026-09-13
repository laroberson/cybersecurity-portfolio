---
layout: case-study
modal-id: 8
title: Linux File Permissions
group: labs
icon: fa-folder-tree
project-url: https://docs.google.com/document/d/1AmcfqaW5OdF_VatnYc2VG2lO8gl-zfWKqL1-W90TwRA/view?usp=sharing
description: Inspected and corrected Linux file and directory permissions, including permissions on hidden files.
scenario: A Linux environment contained files and directories whose permissions needed to be reviewed and adjusted to follow least-privilege principles.
objective: Identify permission issues and apply the correct changes without granting broader access than necessary.
tools:
  - Linux command line
  - File and directory permission strings
  - chmod
tasks:
  - Inspected file and directory metadata to determine current access settings.
  - Interpreted permission strings for user, group, and other access.
  - Updated permissions for standard and hidden files, as well as directories.
findings-label: Skills demonstrated
findings:
  - title: Permission interpretation
    detail: Reading permission strings makes it possible to identify who can read, write, or execute a file or directory.
  - title: Least privilege
    detail: Removing unnecessary permissions reduces the chance that the wrong account can access or alter sensitive resources.
  - title: Directory awareness
    detail: Directory permissions affect the ability to list, access, and modify the resources they contain.
recommendations-label: Next step
recommendations:
  - Review permissions regularly, especially after new users, groups, or files are introduced.
  - Use group ownership deliberately instead of granting broad access to all users.
  - Document permission changes that affect production or security-sensitive resources.
---
