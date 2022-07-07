# dayum_i_troubleshooted

### ! [rejected] master -> master (fetch first)

- git fetch origin master:tmp
- git rebase tmp
- git push origin HEAD:master
- git branch -D tmp

[stackoverflow link](https://stackoverflow.com/questions/28429819/rejected-master-master-fetch-first)


### Updates were rejected because the remote contains work that you do not have locally

[stackoverflow link](https://stackoverflow.com/questions/24357108/updates-were-rejected-because-the-remote-contains-work-that-you-do-not-have-loca)

### No Such Table
[stackoverflow link](https://stackoverflow.com/questions/25771755/django-operationalerror-no-such-table)

### custom token serializer mod

[stackoverflow link](https://stackoverflow.com/questions/53480770/how-to-return-custom-data-with-access-and-refresh-tokens-to-identify-users-in-dj)


### git push origin +sha:branch
### git push origin +be21214:master   + means force
[stackoverflow link](https://stackoverflow.com/questions/448919/how-can-i-remove-a-commit-on-github)

### git rebase be21214 --autostash

[stackoverflow link](https://stackoverflow.com/questions/21358872/git-cannot-rebase-because-of-uncommitted-changes)

### .gitignore
[stackoverflow link](https://stackoverflow.com/questions/56309100/how-to-ignore-the-same-name-directory-pycache-in-a-project)

### git cherry-pick

[stackoverflow](https://stackoverflow.com/questions/41261474/how-to-delete-a-only-a-specific-commit-in-the-middle-of-the-git-log)


### bootstrap modal submit issue : solution by Mofaggol

[stackoverflow](https://stackoverflow.com/questions/31686089/form-submit-button-not-working-in-bootstrap-modal-window)

### redirect to current page after applying pagination : solution by viktor
[stack](https://stackoverflow.com/questions/27325505/django-getting-previous-url)

### script timeout function : solution by shelvington
[stack](https://stackoverflow.com/questions/67854364/how-to-clear-a-validation-error-in-django) 
```
<script>
  setTimeout(function() {
    let errors = document.getElementsByClassName('errorlist');
    while(errors.length > 0) {
      errors[0].parentNode.removeChild(errors[0]);
    }
  }, 3000);
</script>
```

### checking validation in user creation form

[stack] (https://stackoverflow.com/questions/55969952/how-can-i-avoid-a-user-from-registering-an-already-used-email-in-django)
