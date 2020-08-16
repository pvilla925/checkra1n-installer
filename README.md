# Checkra1n Installer
Installer for headless devices that will install Checkra1n and add Webra1n As a Service on the system.

## How to run
```bash
git clone https://github.com/cool5tar/checkra1n-installer
cd checkra1n-installer
bash MAIN.sh
```

### Now what ?
- You can access Webra1n (port `80` by default, you can edit the port by editing the [`webra1n.service`](/webra1n.service) at line 13)
- You can access Checkra1n on SSH (port `22` by default, default user/password is `checkra1n`/`checkra1n` and is sudoer for all checkra1n-related executables)

### How to uninstall
`bash MAIN.sh uninstall`


## Warning
For sileo install odysseyra1n