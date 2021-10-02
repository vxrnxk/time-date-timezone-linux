<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

# time-date-timezone-linux
How to set time, date and timezone in Linux


### CHECK CONFIGS
```bash
timedatectl
```

### CHECK THE STATUS OF TIMEDATECTL 
```bash
timedatectl status
```

### SET THE NTP VALUE TO ZERO 
```bash
timedatectl set-ntp 0
```

### SET TIMEZONE (BR)
```bash
timedatectl set-timezone America/Sao_Paulo
```

### CHANGE THE TIME AND DATE
```bash
timedatectl set-time "YYYY-MM-DD HH:MM:SS"
```
