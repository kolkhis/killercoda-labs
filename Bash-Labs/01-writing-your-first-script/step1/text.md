# Creating the Script File

To create a script, first you need to create a file.  
Once the file is created, you must give it execute permissions.  
Then, you're ready to write your script.


## Solution

<details>
<summary>Solution</summary>

1. Create a file named `hello`.  
   ```bash
   touch hello
   ```{{exec}}

    - Some people prefer to use a `.sh` extension for the shell scripts.
      It doesn't matter if you do.  
    - An argument against a `.sh` file extension: if we were to rewrite
      our program in another (compiled) language, the `.sh` file extension would
      have to be changed everywhere it is used.  

<br />

2. Give the file execute permissions.
   ```bash
   chmod 755 hello
   ```{{exec}}
    - Alternatively, we can use the symbolic notation rather than octal notation:
      ```bash
      chmod u+x hello
      ```{{exec}}

</details>







