# Linux Commands for DevOps

## File and Directory Management

| Command | Purpose |
|---|---|
| `pwd` | Display the current directory |
| `ls -la` | List files, including hidden files |
| `mkdir -p <directory>` | Create directories |
| `touch <file>` | Create an empty file if it does not exist |
| `cp <source> <destination>` | Copy files |
| `mv <source> <destination>` | Move or rename files |
| `rm <file>` | Remove a file |

## System and Disk Management

| Command | Purpose |
|---|---|
| `df -h` | Display filesystem disk usage |
| `lsblk` | List block devices |
| `free -h` | Display memory usage |
| `uptime` | Show system uptime and load averages |
| `whoami` | Display the current username |

## Process and Service Management

| Command | Purpose |
|---|---|
| `ps aux` | Display running processes |
| `top` | Monitor processes and system resources |
| `systemctl status <service>` | Check a systemd service's status |
| `journalctl -u <service>` | View logs for a systemd service |

## Best Practices

- Check the target path before deleting files.
- Use `sudo` only when elevated permissions are needed.
- Review service logs when troubleshooting.
- Verify disk space before deploying applications.
