# Selinuix_DenialsFixer
Generate Fixes for your SELinux Denials


*Cuz I'm also a lazy noob trying to fix his broken enforcing build*.

## Usage

Run into WSL/your preferred Linux terminal: `python3 denials.py`.

You can also run it as a normal executable: `./denials.py`.

### Options allowed

- `-1 denial` outputs only the fix for the inserted denial.
- `-c` cleans up your working directory from unnecessary files.
- `-d file` enables the dmesg parsing mode. Acts like logcat mode.
- `-h` shows the help page.
- `-l file` enables the logcat parsing mode.
- `-s` sanitizes log file encoding before processing it.
- `-v` enables verbose mode. It'll output every denial into its respective file.
