# SLURM and Research Computing Commands Cheatsheet

## SLURM Job Commands

| Command            | Description                         |
|--------------------|-------------------------------------|
| `sbatch`           | Submit a job script                 |
| `squeue`           | View status of jobs in the queue    |
| `sinfo`            | Show information on nodes/partitions |
| `scancel`          | Cancel a running or queued job      |
| `longjob <jobid>`  | Get detailed info about a job       |

---

## Module System Commands

| Command                   | Description                           |
|---------------------------|---------------------------------------|
| `module`                  | Show module command help              |
| `module avail`            | List available modules                |
| `module list`             | List loaded modules                   |
| `module load <name>`      | Load a module                         |
| `module unload <name>`    | Unload a specific module              |
| `module purge`            | Unload all modules                    |
| `module help <name>`      | Show help for a module                |
| `module whatis <name>`    | Get a brief description of a module   |

---

## Secure File Transfer

### CLI Tools
- `rsync`
- `scp`
- `sftp`
- `wget`
- `curl`

### GUI Tools
- FileZilla
- WinSCP
- CyberDuck

### SFTP Commands

| Command         | Description                                      |
|-----------------|--------------------------------------------------|
| `pwd` / `lpwd`  | Show remote / local working directory            |
| `cd` / `lcd`    | Change remote / local working directory          |
| `ls` / `lls`    | List remote / local files                        |
| `mkdir` / `lmkdir` | Create remote / local directory              |
| `put <file>`    | Upload file from local to remote                 |
| `get <file>`    | Download file from remote to local               |
| `bye` / `exit`  | Exit the SFTP session                            |

---

## Recommended Text Editors
- Notepad++
- Sublime Text 2
- Atom
- Komodo Edit
