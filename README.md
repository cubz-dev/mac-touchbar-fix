# mac-touchbar-fix
A simple bash script for resetting macbook touchbar service


Step by step cmds:
```
  $ cd ~
  $ touch touchbar.sh
  $ vim touchbar.sh
```
   Press I (insert) and add following lines:
    
    
    #!/bin/bash
    
    sudo pkill TouchBarServer;
    sudo killall "ControlStrip";
    
   To exit, press ESC and type ":wq"
  
  To run: $ ./touchbar.sh
