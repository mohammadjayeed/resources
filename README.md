# dayum_I_troubleshooted

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

[stack](https://stackoverflow.com/questions/55969952/how-can-i-avoid-a-user-from-registering-an-already-used-email-in-django)

### adding svg in table

[stack](https://stackoverflow.com/questions/21580527/svg-in-table-chrome-firefox-ie)

### change remote origin url

[stack](https://stackoverflow.com/questions/2432764/how-to-change-the-uri-url-for-a-remote-git-repository)

## Important Note on using Django Forms properly : solution by Alioguzhan

[stack](https://stackoverflow.com/questions/37264511/django-forms-returns-error-about-errorlist-when-validating)


## automatic IP detection

[stack](https://stackoverflow.com/questions/4581789/how-do-i-get-user-ip-address-in-django)


## windows SQL PATH solution by khaled mohamed, abubakr elghazawy

[stack](https://stackoverflow.com/questions/5920136/mysql-is-not-recognised-as-an-internal-or-external-command-operable-program-or-b)

## docker zorin installation instruction

- sudo apt update

- sudo apt install ca-certificates

- sudo apt install curl

- sudo apt install gnupg

- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

- echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
$(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

- sudo apt update

- sudo apt-get install docker-ce docker-ce-cli containerd.io

- https://www.youtube.com/watch?v=NEyXDdBrw2c

- sudo gpasswd -a $USER docker

## Prefetch related issue django
[stack](https://stackoverflow.com/questions/71152626/django-how-to-print-the-value-from-a-class-in-the-prefetch-related-class-whic)

## annotation vs aggregation __ reading material : answer by vinay kumar
[stack](https://stackoverflow.com/questions/7981837/difference-between-djangos-annotate-and-aggregate-methods)

## debug flag problem in production server (django)
[stack](https://stackoverflow.com/questions/38617046/django-debug-false-still-runs-in-debug-mode)

## wsgi daemon issue NAME DUPLICATES
[git](https://github.com/certbot/certbot/issues/4880)

## copying files from ec2 instance : answer by kenster
[stack](https://stackoverflow.com/questions/29249562/permission-denied-public-key-while-copying-folder-file-from-local-machine-to-aws)
