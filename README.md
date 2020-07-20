# other-useful-python-and-system-related-command
other useful python and system related command


# crawl the page
    wget -l1 -r -k -np --user-agent="Mozilla/5.0 (iPhone; CPU iPhone OS 7_0 like Mac OS X; en-us) AppleWebKit/537.51.1 (KHTML, like Gecko) Version/7.0 Mobile/11A465 Safari/9537.53" https://www.example.com/example.html


# SCP Copy
    scp -r -i example.pem  ubuntu@0.0.0.0:/home/ubuntu/elacancer /home/tech-pradeep/

# save without sudo
:w !sudo tee %

# pycharm space inscrease
vim /etc/sysctl.conf

    fs.inotify.max_user_watches = 524288
    
sudo sysctl -p



# redis error
    config set stop-writes-on-bgsave-error no



# virtualenv workon 
    sudo apt install virtualenv
    pip install virtualenvwrapper



