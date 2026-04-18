# Writing the Script Content

Now that we have created our script file, we need to add some content to it. 
Let's start by writing a simple script that prints "Hello, World!" to the 
terminal.

## Solution
<details>
<summary>Solution</summary>

1. Open the `hello` script file in a text editor (e.g., `vi`/`vim`, `nano`).
   ```bash
   vi hello
   ```exec
    - Press `i` to enter insert mode in `vi`/`vim`.

2. The first line of any script should be the "shebang" line, which tells the
   system which interpreter to use to execute the script.  
   e.g.,:
   ```bash
   #!/bin/bash
   ```
    - Some prefer to use `#!/usr/bin/env bash` for portability.  
      This will search the system for `bash`, rather than hardcoding it
      to `/bin/bash` (it may not be located there on all systems).

3. Next, we can add the command to pring "Hello, World!" to the terminal:
   ```bash
   echo "Hello, World!"
   ```
   Or, use `printf` for more control over formatting:
   ```bash
   printf "Hello, World!\n"
   ```
    - `printf` does not output a newline at the end of the string by
      default, so we need to include `\n`. 

4. After adding the content, save the file and exit the editor.  
    - In `vi`/`vim`, press `Esc` to exit insert mode, then type `:wq` and press `Enter` to save and quit.

</details>



