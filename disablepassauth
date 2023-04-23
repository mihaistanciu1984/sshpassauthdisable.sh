#/bin/sh
echo "Disable Password Authentication"
sshd_config_file="/etc/ssh/sshd_config"
sed -i 's/PasswordAuthentication yes/PasswordAuthentication no/' ./sshd_config
echo "Restart SSHDaemon"
sudo systemctl restart sshd
