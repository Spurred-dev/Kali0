# Kali02. 
Install dirmngr and apt-transport-https if not already installed
apt-get install dirmngr apt-transport-https
3. Add the Windscribe signing key to apt as root
apt-key adv --keyserver keyserver.ubuntu.com --recv-key FDC247B7
4. Add the repository to your sources.list
sh -c "echo 'deb https://repo.windscribe.com/debian buster main' > /etc/apt/sources.list.d/windscribe-repo.list"
5. Run apt-get update
apt-get update
6. Install windscribe-cli
apt-get install windscribe-cli
7. Switch to non-root user
exit
8. Login to Windscribe
windscribe login
9. Connect to Windscribe
windscribe connect
Need help?
windscribe --help
