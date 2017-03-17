# Resync-git-repo-with-new-gitignore-file


<pre>
# rm all files
git rm -r --cached .
</pre>

<pre>
# add all files as per new .gitignore
git add .
</pre>

<pre>
# now, commit for new .gitignore to apply
git commit -m ".gitignore is now working"
</pre>

<pre>
#now push to the master branch
git push origin master
</pre>
