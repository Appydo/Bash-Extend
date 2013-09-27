Bash Extend
======

Sample alias for extend bashrc and saving your time.


INSTALL
-------

To create an alias permanently add the alias to your .bashrc file

    wget https://raw.github.com/Appydo/Bash-Extend/master/alias -O /etc/bash.bashrc_extend;echo ". /etc/bash.bashrc_extend" >> /etc/bash.bashrc;source /etc/bash.bashrc

Update

    update_bashrc_extend

Remove 

    remove_bashrc_extend
    

EXAMPLE
-------

    aptu    = aptitude update;aptitude upgrade;
    updatey = apt-get --yes update && apt-get --yes upgrade
    ...     = cd ../..
    ll      = ls -lv --group-directories-first
    l       = ls
    home    = cd ~
    755     = chmod 755
    sha1    = openssl sha1
    meminfo = free -m -l -t
