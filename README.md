# ansible-usecases


##project path - "/home/main/projects/ansible-usecases"
## first prepare your machine with run prepare.sh shell script

## replace your username in code that has uid and gid 1000. in my case username is main so you can search main entry in given file location and replace it with your user.

## username replace in "environments/localhost/group_vars/all/default.yml" &  "environments/localhost/hosts" , replace ip in hosts file also.

## then run " ./run.sh elastic " commnad to install elasticsearch using ansible

## make sure scripts has execute permission. and also make sure your user must have sudo privilages and docker privilages also to run it.

##go to this location of laptop "/home/main/baha_june_2023/tass-projects-bsk-Adding-componentes-to-deployment" and copy required playbooks and roles directory in code structure, then you will able to deploy more components using jenkins.

##playbook will add on root location of project and roles will copy in roles directory

## After adding playbook and roles to code structure you have to push chnages on git, so follow these commands.

git status ##it will show chnages to push
git add . ##this will add chnages that will push to repo
git commit -m "commit message" 
git push

