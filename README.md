# django_learn

### Useful commands

**_deactivate_** — Выход из текущей виртуальной среды Python
**_workon_** — Список доступных виртуальных сред
**_workon name_of_environment_** — Активация конкретной виртуальной среды Python
**_rmvirtualenv name_of_environment_** — Удаление конкретной виртуальной среды.

### Prepare
   
 1/ Install virtual environment.
   
 ```bash
 $ sudo pip3 install virtualenvwrapper
 ```  
   
 2/ Add to /home/{$user}/.bashrc
 
 ```
export WORKON_HOME=$HOME/.virtualenvs 
export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3 
export VIRTUALENVWRAPPER_VIRTUALENV_ARGS=' -p /usr/bin/python3 ' 
export PROJECT_HOME=$HOME/Devel 
source /usr/local/bin/virtualenvwrapper.sh
 ```  
   
 3/ Reload .bashrc
 
 ```bash
 $ source ~/.bashrc
 ```
 
 4/ Create venv for project
  
 ```bash
 $ mkvirtualenv <your_venv_name>
 ```
 
 5/ Create venv for project
  
 ```bash
 $ mkvirtualenv <your_venv_name>
 ```
