# Introdução ao ReactJS 

## Project forked from [Github Tautorn - Introduction-reactjs](https://github.com/Tautorn/introduction-reactjs.git)


1. npm init
2. npm install –save react@16.8.6 react-dom@16.8.6 react-scripts@3.0.1
3. npm start 

Obs.: 

Resolvendo Error: ENOSPC: System limit for number of file watchers reached no Ubuntu.

Digitei no terminal o comando a seguir para poder editar o arquivo “sysctl.conf”:
	
sudo gedit /etc/sysctl.conf

Adicionei a linha a seguir: 
fs.inotify.max_user_watches=524288

Fechei o gedit, em seguida no terminal digitei o comando a seguir para aplicar a nova configuração: sudo sysctl -p
