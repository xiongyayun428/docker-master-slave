# docker-master-slave
docker master slave


# Command line instructions

## Git global setup
```
git config --global user.name "熊亚运"
git config --global user.email "xiongyayun428@163.com"
```

## Create a new repository
```
git clone https://github.com/xiongyayun428/docker-master-slave.git
cd docker-master-slave
echo "# docker-master-slave" >> README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

## Existing folder
```
cd existing_folder
git init
git remote add origin https://github.com/xiongyayun428/docker-master-slave.git
git add .
git pull origin master
git commit -m "Initial commit"
git push -u origin master
```

## Existing Git repository
```
cd existing_repo
git remote rename origin old-origin
git remote add origin https://github.com/xiongyayun428/docker-master-slave.git
git push -u origin --all
git push -u origin --tags
```