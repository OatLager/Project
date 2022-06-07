# Install 
link : https://docs.px4.io/v1.12/en/dev_setup/dev_env_linux_ubuntu.html

0. git install
    - sudo apt install git

1. Dawnload PX4 Source Code
    - git clone https://github.com/PX4/PX4-Autopilot.git --recursive

2. Select PX4 version 
    - git checkout stable or v1.12.3 

3. check version 
    - git log

4. submodule update
    - git submodule update

5. Run the ubuntu.sh to install everything(Toolchains, Gazebo, jMavSim)
    - bash ./PX4-Autopilot/Tools/setup/ubuntu.sh
