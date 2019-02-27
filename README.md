# Piñol's Adventure
[explain the game concept here]

## Table of Contents
1.  Developed With
2.  Using This Repo

## 1. Developed With
- [Godot](https://www.godot.com) - The DE used
- [Piskelapp](https://www.piskelapp.com/) - The pixel sprite editor used

## 2. Using This Repo
1. Open the Terminal and execute the following command:

   ```mkdir ~/repos```

2. Next, you clone the git:

   ```git clone git@github.com:cazpa/pa.git```

3. Go into `~/repos/pa` and switch from the master branch to developement:

   ```git checkout developement```

4. Update the developement repository with:

   ```git pull```

Once you have made your changes and wish to upload it to the project, use the following line:
```
git add [path_to_changed_directories]/*
git commit -am "PA-XXXX Initial implementation"
git push --set-upstream origin developement/PA-XXX
```
