# robotInterface
user interface using Rosbridge Nodejs

# Installation Nodejs
 ```
  sudo apt-get update -y && sudo apt-get upgrade -y

  #Install Nodejs
  curl -sL https://deb.nodesource.com/setup_18.x -o nodesource_setup.sh
  sudo bash nodesource_setup.sh
  sudo apt-get install -y nodejs

  #checking installation
  node -v
  npm -v

  #Install ReactJS
  npm install -g create-react-app

  create-react-app --version

  #create project
  create-react-app {$projectName}

  #launch nodejs
  npm start
 ```

# Installation Rosbridge
  ```
  sudo apt install ros-<ROS_DISTRO>-rosbridge-server

  source /opt/ros/<ROS_DISTRO>/setup.bash

  #launch rosbridge on terminal
  ros2 launch rosbridge_server rosbridge_websocket_launch.xml
  ```

Make sure running both server
