# chocolatey-backup-restore

Backup and restore [chocolatey](https://chocolatey.org) installation.

`Backup` or `Export` and `Installation` commands need an elevated command shell with admin rights. (`Run as Administrator`)

# backup

Execute backup script `./src/backup-choco-setup.ps1`.

# restore

Use this command to restore all packages in a `packages.config` file.

`choco install packages.config -y`
