# NGINX setup with Visual Studio Code Dev Container
####
### Prerequisite
1. Docker
2. Visual Studio Code

### Setup DevContainer for Visual Studio Code 
1. Create folder (nginx-docker-container) 
2. Start Visual Studio Code and open this folder 
3. Install DevContainer extension for VS Code if it has not been installed
4. Press CTRL + SHIFT + P
5. Type DevContainers, then you will see a list of options, choose Add Dev Container Configuration Files ...
![alt add devcontainer configuration files](https://github.com/eddy-mei/nginx-docker-container/blob/main/docs/add-dev-container-config-file.png?raw=true)
6. Alternatively, for steps 4 & 5, clicking the green DevContainer gadget at the bottom left corner of VS Code will do the same trick  
![alt devcontainer gadget](https://github.com/eddy-mei/nginx-docker-container/blob/main/docs/dev-container-gadget.png?raw=true)
7. Choose the Alpine predefined base container image 
8. Install NGINX on top of the base image to work with
9. Install node.js, npm, git, zsh, etc.

#####
# Create node project
1. Geneate tsconfig.json with the following command   
  npx tsc --init
2. Generate package.json with npm command  
  npm init 
3.  
