## Investigation Findings

Investigation of the process execution revealed that `/usr/bin/python3 /tmp/update.py` was launched with PPID = 1, indicating initiation by systemd rather than an interactive shell. The process was executed as the root user, confirming system-level privileges. Further analysis identified a custom systemd timer and service configured to execute the script every 60 seconds, demonstrating automated and persistent behavior. The recurring execution from the `/tmp` directory was inconsistent with legitimate administrative workflows.
