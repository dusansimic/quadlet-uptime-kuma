# Uptime Kuma with Quadlet

## What is this?

| Task         | Tool        |
|--------------|-------------|
| Provisioning | Ansible     |
| Testing      | Vagrant     |
| Managing     | Quadlet     |
| Service      | Uptime Kuma |

## Ansible roles

### [accounts](ansible/roles/accounts/)

Create a container manager user account and enable lingering for it.

### [uptime_kuma](ansible/roles/uptime_kuma/)

Create container and volume unit files, enable them and start them. The unit
files are stored in container magaer user directory.

Check role variables for default values which can be modified for different
deployments.

## Author

Dušan Simić <dusan.simic1810@gmail.com>

## License

[MIT](LICENSE)
