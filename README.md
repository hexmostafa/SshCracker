# SSH Tools - Checker & Cracker

A powerful tool for SSH checking and cracking, provided as an executable (EXE) file. It includes two main utilities:
- **SSH Checker**: Scans a list of IP:Port combinations to find active SSH services.
- **SSH Cracker**: Attempts to brute-force SSH servers using IP, username, and password lists.

## Features
- Multi-threaded for fast performance
- Real-time stats display (attempts, successes, speed, etc.)
- Results saved in `results/checker` and `results/cracker` folders
- Optional SSH key support
- Adjustable timeout and delay settings

## How to Use
1. **Download the EXE**:
   - Grab the latest `SshCracker.exe` from the [Releases]([https://github.com/yourusername/ssh-tools/releases](https://github.com/hexmostafa/SshCracker/releases/tag/SshCracker)) section.

2. **Run the Tool**:
   - Place the `SshCracker.exe` in a suitable location (e.g., Desktop or a folder with write permissions).

3. **Run the Tool**:
   - Double-click `SshCracker.exe` or run it via terminal:

  You'll see a menu like this:

    ╔════════════════════════════════════╗
    ║ Created By: @HEXMOSTAFA            ║
    ╠════════════════════════════════════╣
    ║ 1. SSH Checker                     ║
    ║ 2. SSH Cracker                     ║
    ║ 3. Exit                            ║
    ╚════════════════════════════════════╝
Select an Option:
  Type 1 for Checker, 2 for Cracker, or 3 to exit, then press Enter.

4.Follow the Prompts:
  For Checker: Enter the IP list file path, thread count, and batch size.
  For Cracker: Enter IP list, user list, password list, thread count, timeout, delay, and optionally an SSH key path.
  password list (e.g., passwords.txt), thread count, timeout, delay, and optionally an SSH key path.

5.Check Results:
  Checker: results/checker/good.txt (active SSH) and results/checker/bad.txt (inactive)
  Cracker: results/cracker/good_access.txt (full access),
  results/cracker/good_non_access.txt (login only),
  results/cracker/failed_attempts.txt, and results/cracker/error_log.txt

Notes :
  Run the tool in a folder where you have write permissions (e.g., Desktop).
  On Windows, if you see a security warning, click "Run anyway".

