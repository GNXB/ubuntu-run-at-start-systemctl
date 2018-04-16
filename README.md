# ubuntu-run-at-start-systemctl
Example config .service for systemctl

## How to make Ubuntu apps run at start
ref: https://askubuntu.com/questions/919054/how-do-i-run-a-single-command-at-startup-using-systemd (https://askubuntu.com/a/919059)

```bash
sudo systemctl start myapp.service
sudo systemctl stop myapp.service
sudo systemctl enable myapp.service
```
