# NEW PROJECT

`New project` is a test project. Maybe someday magic will happen here. Who knows :)

## Instruction

```bash
mkdir new-project && cd new-project           # create new directory and go to that directory
git init                                      # initialize new empty Git repository
touch README.md                               # create README file
nano README.md                                # write some text in README file
git add README.md                             # add changes in the README.md file to the Git index
git commit -m "init"                          # make your first commit
git checkout -b development                   # checkout to new "development" branch
nano README.md                                # write down the instruction
git commit -m "README instruction created"    # commit changes
git checkout main                             # checkout to main branch
git merge development                         # merge changes from "development" branch into "main"
git status                                    # make sure all your changes is committed
git remote add origin 
https://github.com/<OWNER>/<REPOSITORY.git    # create new remote Github repository
git push origin main                          # push your project to Github repository
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.