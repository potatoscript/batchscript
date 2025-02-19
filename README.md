# Batch Script Cheat Sheet

| Title | Remark |
|-------|--------|
| [Introduction to Batch Scripting](https://github.com/potatoscript/batchscript/wiki/Introduction) | Learn the basics of batch scripting, including syntax and use cases. |
| [Running Batch Files](https://github.com/potatoscript/batchscript/wiki/Running-Batch-Files) | Understand how to create and execute `.bat` or `.cmd` files on Windows. |
| [Environment Variables](https://github.com/potatoscript/batchscript/wiki/Environment-Variables) | Learn how to set, retrieve, and use environment variables. |
| [File and Directory Operations](https://github.com/potatoscript/batchscript/wiki/File-and-Directory-Operations) | Perform file and directory manipulations such as creating, copying, moving, and deleting. |
| [Conditional Statements](https://github.com/potatoscript/batchscript/wiki/Conditional-Statements) | Implement logic using `IF`, `ELSE`, and nested conditions. |
| [Loops in Batch](https://github.com/potatoscript/batchscript/wiki/Loops) | Automate repetitive tasks using `FOR` and `WHILE` loops. |
| [User Input and Arguments](https://github.com/potatoscript/batchscript/wiki/User-Input-and-Arguments) | Handle user input and pass arguments to batch scripts. |
| [Logging and Debugging](https://github.com/potatoscript/batchscript/wiki/Logging-and-Debugging) | Log outputs to files and debug batch scripts effectively. |
| [Backup Database Data](https://github.com/potatoscript/batchscript/wiki/Backup-Database-Data) | Create a batch script to automate database backups. |
| [Shortcut File](https://github.com/potatoscript/batchscript/wiki/Shortcut-File) | Learn how to create shortcut files using batch scripting. |
| [Network Operations](https://github.com/potatoscript/batchscript/wiki/Network-Operations) | Automate network-related tasks like pinging and retrieving IP configurations. |
| [Clearing Used Ports](https://github.com/potatoscript/batchscript/wiki/Clearing-Used-Ports) | Learn to free up ports by identifying and killing processes. |
| [Advanced Scripting](https://github.com/potatoscript/batchscript/wiki/Advanced-Scripting) | Explore advanced techniques like error handling and branching logic. |
| [Scheduling Batch Scripts](https://github.com/potatoscript/batchscript/wiki/Scheduling) | Automate script execution using Task Scheduler. |
| [Best Practices](https://github.com/potatoscript/batchscript/wiki/Best-Practices) | Follow tips and tricks for writing efficient and maintainable batch scripts. |

---

## Clearing Used Ports

1. **Find the PID of the Port**  
   ```bash
   netstat -ano | findstr portNumber
   ```
   Replace `portNumber` with the port you want to clear.

2. **Kill the Process**  
   ```bash
   taskkill /F /PID the_pid_number
   ```
   Replace `the_pid_number` with the PID retrieved in the previous step.

---

## Additional Resources

- 📖 [Official Documentation](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands)  
- 🎥 [Video Tutorials](https://www.youtube.com/results?search_query=batch+scripting+tutorial)  
- 📂 [Sample Projects](https://github.com/topics/batch-scripts)  

