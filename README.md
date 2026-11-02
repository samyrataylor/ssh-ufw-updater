# SSH UFW updater

Clone the repository

```bash
$ git clone https://github.com/samyrataylor/ssh-ufw-updater
```

Allow execution

```bash
$ chmod +x ufw-updater
```

Run

```bash
$ ./ufw-updater
```

Add Cron Job

```
0 1 * * * /path/to/repository/ufw-updater >> /path/to/repository/cronjob.log 2>&1
```
