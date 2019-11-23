# 快捷键与各种功能按键记录

### Windows
1. Alt + Tab
2. Ctrl + Tab
3. Win + Tab
4. Win + Ctrl + left/right: change the Windows table when having several table in Win + Tab
5. Win + left/right/up/down: change the direction or size of the window of different App
6. Win + W: open the workarea of Windows (can use notes etc.)
7. Win + I: open computer setting
8. Win + Shift + S: Screen Clipping in Windows

### postgresDB
1. psql -U postgres: enter the postgresDB
2. \l: show the list of databases
3. CREATE DATABASE db_name: create a new database
4. DROP DATABASE db_name: remvoe a existed database
5. \c db_name: connect to the database
6. \d: show all in the database
7. \dt: show tables in the database
8. \q: exit the database

### docker
1. docker image: show the existed images
2. docker ps -a: show the running container
3. docker search image: see if the image exist
4. docker pull image: get the image to local
5. docker start/stop/restart container_name/container_id
6. docker rm container_name/container_id: remove a container
7.  docker ps -a -q: show all the running and stopped container
8.  docker rm $(docker ps -a -q): remove all stopped containers
9.  docker rmi image_id: remove images
10. exit: exit the container
11. docker exec -it container_id bin/bash: get into the container's environment
12. docker run --name container_name -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:alpine: pull and run a postgresdb container
13. docker run -d -p 6379:6379 --name redis1 redis: pull and run a redis container
14. docker exec -it redis1 sh: enter the redis container


### virtualenv
1. virtualenv -p python-version virtual-environment-name: create a virtual environment

### Chrome
1. Ctrl + Win + number: jump to certain webpage

### Ubuntu
1. ps -ef|grep process: see if the process exist
2. kill -QUIT/-TERM
3. curl: https://www.cnblogs.com/cangqiongbingchen/p/10180535.html
4. source activate: start virtual environment of python in ubuntu server

### Vim

### tmux
1. tmux new -s name: create a new session on tmux
2. tmux ls: see all session
3. tmux a/attach -t name: open current session
4. tmux kill-session -t name: kill one session
5. tmux detach/ctrl + b + d: exit session
6. ctrl + B + %/": separate pane in one session
7. ctrl + B + direction/o: change pane 
8. ctrl + B(hold) + direction： change pane size
9. ctrl + B + c: separate new window in one session
10. ctrl + B + p/n: change window
11. exit: exit a window or pane or kill a session

### VS Code相关
##### VS Code操作
1. Alt + left/right: change file in the top list
2. Ctrl + Shift + N: jump to some file by input
3. Ctrl + Tab: jump to some file by selection
4. Ctrl + Shift + L: multi-select in text
5. Ctrl + /: adding commit fastly in certain file
6. Fn + direction: jump in the text content
7. Ctrl + L: select this line
8. Ctrl + G: jump to certain line
9. F12: jump to function

##### html:
1. ! + tab: fastly construct html template

##### React:
1. cc: create class template in React
2. sfc: create function template in React
3. imrc: import React, {component} from 'react';
4. cdm: componentDidMount()