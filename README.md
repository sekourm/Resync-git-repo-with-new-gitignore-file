-- Resync git repo with new gitignore file --

# rm all files
<pre>
git rm -r --cached .
</pre>

# add all files as per new .gitignore
<pre>
git add .
</pre>

# now, commit for new .gitignore to apply
<pre>
git commit -m ".gitignore is now working"
</pre>

# now push to the master branch
<pre>
git push origin master
</pre>
