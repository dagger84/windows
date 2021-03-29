# jobs and processes

- A **process** contains a set of resources used when executing an instance of a program:
  - a private virtual address space, used to prevent a process to access or
    modify other processes’ or operating system data
  - an executable program, which is mapped into the process’ private virtual
    address space
  - a security context (called access token), which includes identification of
    the user, security groups, privileges, etc.
  - a process ID
  - one or more threads of execution

- A group of processes can be managed as a unit called a **job**.

## references
- [Windows Privilege Escalation: An approach for penetration testers](https://sec-consult.com/blog/detail/windows-privilege-escalation-an-approach-for-penetration-testers/)
