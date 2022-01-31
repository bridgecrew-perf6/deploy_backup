# deploy_backup
Ansible playbook that deploys a script to collect and upload backups to remote HTTP server. Intended for use with [go-simple-upload-server](https://github.com/devusb/go-simple-upload-server) where `backup_url` is in the format of:
```
http://localhost:25478/files/upload?token=f9403fc5f537b4ab332d
```