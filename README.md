# cybersecurity-internship-task4

# Firewall Setup on Kali Linux using UFW

## Steps Performed:
1. Installed UFW: `sudo apt install ufw`
2. Set default policies: 
   - `sudo ufw default deny incoming`
   - `sudo ufw default allow outgoing`
3. Allowed SSH: `sudo ufw allow 22/tcp`
4. Blocked Telnet: `sudo ufw deny 23/tcp`
5. Enabled UFW: `sudo ufw enable`
6. Verified rules: `sudo ufw status numbered`

## Screenshots:
- See attached screenshots of the commands and results

## Key Learnings:
- UFW simplifies firewall management with easy commands
- Understanding inbound/outbound rules
- Importance of allowing SSH before enabling the firewall
- Why Telnet should be blocked (unencrypted protocol)
EOF
