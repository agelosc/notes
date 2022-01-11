#### Init
```
# create empty repo
git init

# Add all files
git add .

# first commit
git commit -m "initial"

# set origin to github.com
git remote add origin git@github.com:agelosc/<repo>

# alternative way to set origin
git remote add origin https://github.com/agelosc/repo

 # Push to origin
git push -u origin master
```

#### Nerve Install
```
git init
git remote add origin https://github.com/agelosc/nerve
```


#### Nerve Update
```
git fetch --all
git reset --hard origin/master
```
