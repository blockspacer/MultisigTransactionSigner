XEMSign is a windows deployed bot which signs multisignature transactions based on a predefined rule set which is easily configured via the app.config file. All transactions are signed locally and the host machine is never communicated with directly making it a highly secure signing mechanism. 

It supports multiple private keys and will monitor any multisignature accounts those keys are cosignatory on.

To run XEMSign on linux, install Mono

    sudo apt-get install mono-complete
    
Then execute 

    mono XEMSign.exe
