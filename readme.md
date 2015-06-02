# torrentbox example config
This example config demonstrates the necessary config to use the torrentbox cookbook
you will need to:  

1. Install Chef using wget to download and dpkg -i  to install the .deb file  
2. Package from berks on your computer with chef-dk installed using "berks package"
3. Copy generated packaged to the server (e.g. via sftp)
3. Cd to /opt/chef and extract the tar.gz (e.g.`tar -xvzf /home/user/cookbooks-1433179302.tar.gz`)
4. Copy the rest of the files in the configuration to `/opt/chef`
5. Run chef!  `sudo chef-client -z -c /opt/chef/client.rb`
