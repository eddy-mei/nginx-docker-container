# NGINX setup with Visual Studio Code Dev Container
Setup DevContainer for Visual Studio Code 
1. Create folder (nginx-docker-container) 
2. Start Visual Studio Code and open this folder 
3. Install DevContainer extension for VS Code if it has not been installed
4. Press CTRL + SHIFT + P
5. Type DevContainers, then you will see a list of options, choose Add Dev Container Configuration Files ...
![alt add devcontainer configuration files](https://github.com/eddy-mei/nginx-docker-container/blob/main/docs/add-dev-container-config-file.png?raw=true)
6. Alternatively, for steps 4 & 5, clicking the green DevContainer gadget at the bottom left corner of VS Code will do the same trick  
![alt devcontainer gadget](https://github.com/eddy-mei/nginx-docker-container/blob/main/docs/dev-container-gadget.png?raw=true)
7. Choose the Node.js & TypeScript predefined base container image, or Node.js & Javascript base container image  
8. Install NGINX on top of the base image to work with
