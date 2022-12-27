<h1 align="center">✋ BEWARE ✋</h1>

## If you are a 42 Student, do not copy/paste this project, it will be considered cheating and you will be grated -42.

# 42 Wolfsburg Piscine November 20222
## Shell_01

# Contents

1. [Exercise 01 : print_groups](#ex01)
2. [Exercise 02 : find_sh](#ex02)
3. [Exercise 03 : ](#ex03)
4. [Exercise 04 : ](#ex04)
5. [Exercise 05 : ](#ex05)

# <a name="ex01">Exercise 01 : print_groups</a>

| ![Logo_Monolith_small](https://user-images.githubusercontent.com/120580537/209333599-dc44418d-8ee7-42b6-8a4a-7ff328778d87.png) | Exercise 01 |
|-------------------------------------------------------|--------------------------------------------------|
| | print_groups.sh |
| Turn-in directory: | ex01/ |
| Files to turn in: | print_groups.sh |
| Allowed functions: | None |

* Write a command line that will display the list of groups for which the login, contained in the environment variable FT_USER , is a member. Separated by commas without spaces.

* Examples:
  * for FT_USER=nours, the result is "god,root,admin,master,nours,bocal" (without quotation marks)

```
$>./print_groups.sh
god,root,admin,master,nours,bocal$>
```

  * for FT_USER=daemon, the result is "daemon,bin" (without quotation marks)

```
$>./print_groups.sh
daemon,bin$>
```

### 💡 [man](https://man7.org/linux/man-pages/man1/id.1.html) **id** 💡

<p align="right">
 <a href="https://github.com/Cerberus2290/Shell_01#-beware-">back to top</a>
</p>

# <a name="ex02">Exercise 02 : find_sh</a>

| ![Logo_Monolith_small](https://user-images.githubusercontent.com/120580537/209333599-dc44418d-8ee7-42b6-8a4a-7ff328778d87.png) | Exercise 02 |
|-------------------------------------------------------|--------------------------------------------------|
| | find_sh.sh |
| Turn-in directory: | ex02/ |
| Files to turn in: | find_sh.sh |
| Allowed functions: | None |

* Write a command line that searches for all file names that end with ".sh" (without quotation marks) in the current directory and all its sub-directories. It should display only the file names without the .sh.

* Example of output:

```
$>./find_sh.sh | cat -e
find_sh$
file1$
file2$
file3$
$>
```

<p align="right">
 <a href="https://github.com/Cerberus2290/Shell_01#-beware-">back to top</a>
</p>
