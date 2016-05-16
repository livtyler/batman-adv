# batman-adv
Batman-adv Bash script to setup Batman-adv mesh network on Raspbian, compatible with Pi3.

batman-node will install and configure a batman-advance node that can be configured to connect to a batman-adv bridge.

batman-bridge will isntall and setup a batman-bridge that will connect to the internet.

Useage:
You should comment and uncomment the aprts that you need, read the comments in the scripts carefully parts can be done manually or automatically, if you dont know what you are doing comment/uncomment the parts you want to use.

May require sudo sed -i -e 's/\r$//' FILENAME.bash (Replace FILENAME with whatever you called the file) to work.
May need to chmod 777 the file prior to running.
make sure to resize image using sudo raspi-config.
Please run as Sudo.
