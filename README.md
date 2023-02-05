# DVC Practice

[DVC](https://dvc.org/doc/start)

## Steps:

```bash
    git init
```

* create the files and push it to github

* list the URL of the remote repo:
```bash
    git remote -v
```

* install dvc:
```bash
    pip install dvc
```

```bash
    dvc init
```

* We will use google drive to store our data [setup google drive](https://dvc.org/doc/user-guide/how-to/setup-google-drive-remote#url-format)

* Setting 'myremote' as a default remote [data-versioning](https://dvc.org/doc/start/data-management/data-versioning)
```bash
    dvc remote add -d my-rem gdrive://Copied_ID
```

* Push the ccde to github

* Get the dataset

```bash
    dvc add data.csv
```


* commit and push the code to github
```bash
    git add . && git commit -m "start tracking data"
    git push origin main
```

* add the DVC tracked data file to our DVC repository
``` bash
    dvc push
```
```bash 
    pip install dvc-gdrive
```


