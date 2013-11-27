AAAAAH, that took way too long to figure out :P

My changes are on the git branch "trb".
On 11/27/13 trb was branched from 4.8-MAINT and then my expiration changes were merged.


To update in the future: -- I think the following will work
git rebase 4.X-MAINT

If you change anymore files:
git add <file>
git commit <file>
