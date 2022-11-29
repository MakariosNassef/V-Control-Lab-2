1- creat Repo with name **V-Control-Lab-2**

2- V-Control-Lab-2 git init git remote add origin
**https://github.com/MakariosNassef/V-Control-Lab-2**

3- Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo

**test** https://github.com/MakariosNassef/V-Control-Lab-2/tree/test

**dev**  https://github.com/MakariosNassef/V-Control-Lab-2/tree/dev

--> push the files into branchs
    :+1:git add . 
    :+1:git commit -m "test" 
    :+1:git push origin [bransh-name]
    
5- merge my two branchs to master lacaly when i was in master git merge dev git merge test

6- for push my local master to remote with Command line
$ git push origin master with pull request in github

7- to remove a bransh localy & remotely
$ git bransh -d BRANSHNAME  
$ git push origin :BRANSHNAME

8- Create an annotated tag with tagname (v1.7).
$ git tag -a v1.7 -m "New versio v1.7"

9- Push it to the remote repository.
$ git push origin v1.7

10- Tell me how to list tags.
$ git tag

11- Tell me how to delete tag locally and remotely.
$ git tag -d v1.7 git push origin --delete v1.7

12- image

![This is an image](https://i.redd.it/gw8idnezl1i91.png)
