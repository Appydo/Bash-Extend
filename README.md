Bash Extend
======

Sample alias for extend bashrc and saving your time.


INSTALL
-------

    wget https://raw.github.com/Appydo/Bash-Extend/master/alias -O /etc/bash.bashrc_extend;echo ". /etc/bash.bashrc_extend" >> /etc/bash.bashrc;source /etc/bash.bashrc

UPDATE
------

    update_bashrc_extend

REMOVE
------

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
