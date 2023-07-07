# manifest
Create the manifest
Repo manifest used to clone the multiple project repo with the help of single command. 
Create the default.xml file under the mainfest
# default.xml
The defualt.xml file will caontains the path of your projects repository. Speficy the projects you want to clone at once into that default.xml file.
# Init
Initilize the repo for manifest. 
repo init -u <"Path of your remote repository"> -b <Branch>
# Sync
Once repo is initilized do the sync to download the project.
repo sync
