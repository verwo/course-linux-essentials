# The Command Line Challenges

Below are detailed explanations for each challenge along with the commands used to verify the information from the man pages.

---

## ✅ The man command

**Description:**  
The `man` command displays the manual pages for other commands. It provides detailed documentation—including usage, options, and examples—to help users understand how to use various commands.

> **Command used:**  
> ```bash
> man man
> ```

---

## ✅ The whoami command

**Description:**  
The `whoami` command outputs the username of the current user executing the command. It essentially tells you “who you are” as recognized by the system.

> **Command used:**  
> ```bash
> man whoami
> ```

---

## ✅ The uptime command

**Description:**  
The `uptime` command shows how long the system has been running since its last reboot. It also displays the number of users currently logged in and the system's load averages for the past 1, 5, and 15 minutes.

> **Command used:**  
> ```bash
> man uptime
> ```

---

## ✅ Help on ls

**Description:**  
The `ls` command does not display help information when running `ls -h` because the `-h` option is interpreted as “human-readable” for file sizes (especially useful with the `-l` option). To see help information for `ls`, you would typically use `ls --help` instead.

> **Command used:**  
> ```bash
> man ls
> ```

---

## ✅ Hidden files

**Description:**  
Hidden files in Linux are files whose names start with a dot (`.`). They are not listed by default when you run `ls`. To list all files, including hidden ones, you can use the `-a` flag with `ls` (i.e., `ls -a`).

> **Command used:**  
> ```bash
> man ls
> ```

---

## ✅ Special Directories

**Descriptions:**  
- **`~`**: Represents the home directory of the current user.
- **`.`**: Represents the current directory.
- **`..`**: Represents the parent directory of the current directory.
- **`/`**: Represents the root directory of the filesystem.

> **Note:**  
> These are standard conventions found in shell and filesystem documentation and are typically confirmed through common usage.

---

## ✅ What shells are available

**Description:**  
You can get a list of all available shells on your system by viewing the contents of the `/etc/shells` file. For example, running the following command will display the list of shells installed on your system:
> ```bash
> cat /etc/shells
> ```

> **Command used:**  
> ```bash
> cat /etc/shells
> ```

---

## ✅ What date is it

**Description:**  
To display the current date and time in the terminal, you can simply use the `date` command. Typing `date` will output the current system date and time.

> **Command used:**  
> ```bash
> man date
> ```

---
