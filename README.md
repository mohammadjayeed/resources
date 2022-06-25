# dayum_i_troubleshooted

### ! [rejected] master -> master (fetch first)

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

[Reference](https://stackoverflow.com/questions/28429819/rejected-master-master-fetch-first)
