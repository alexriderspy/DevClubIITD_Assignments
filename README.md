For anyone facing problems in git
Series of steps to be followed::
a. git clone "link"
b. make all changes 
c. git add filename.py (better )  if issues try git add .
d. git commit -m"done"
e. git push origin master

ERROR:
 error: src refspec master does not match any
happens when we have conflicts that cannot be merged

one option could be to use git push -f origin master but 
it will rewrite everything so not recommended

Now we basically need to merge conflicts so what we do is
1. git pull origin master
or maybe only git pull
2. merge all conflicts manually
3. git push origin master

done