nn_init
=======

Init Script for newznab that incorporates all the steps to run a successful indexer.

Requirements:

    php-prowl-cli : https://github.com/gwelsted-design/php-prowl-cli
    
Usage:

    copy to /etc/init.d

    chmod +x newznab
  
    update-rc.d install newznab
  
    sudo service newznab start
  
  ** Make sure all the paths match your install
