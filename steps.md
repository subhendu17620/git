i am expecting you have already configured your github.if not, 
open cmd
1. clone the remote repo to local machine
    `git clone [link of online repo]`
2. goto that directory which you just cloned using `cd [file neme]`
3. `git init`
4. copy/make your changes to the local directory you just cloned
5. `git pull`
6. for syncronizing all the files use `git add .`
        else `git add [file name]`
7. `git commit -m "message under double quotes"`
    e.g `git commit -m "updated file"`
8. `git push`
    it will syncronize to master branch