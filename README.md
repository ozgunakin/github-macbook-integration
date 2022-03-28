# Github Macbook Integration

## Step 1 - Create a Repo on GitHub <a href="#step-1-install-java" id="step-1-install-java"></a>

* [x] Check "Add a README file".

![](<.gitbook/assets/image (1).png>)

## Step 2 - Clone the Repo from GitHub  <a href="#step-2-configure-ssh" id="step-2-configure-ssh"></a>

* [x] Copy HTTPS address of your repo.

![](<.gitbook/assets/image (4).png>)

* [x] Open your teminal and go to the directory that you want to integrate with github

```
mkdir github
cd github
```

* [x] Clone the directory using git clone command.

```
git clone https://github.com/ozgunakin/github-macbook.git
```

* [x] Change your directory to cloned directory.

```
cd github-macbook
```

* [x] Check git status

```
git status
```

* [x] Output

![](.gitbook/assets/image.png)

## Step 3 - Adding a New File <a href="#step-2-configure-ssh" id="step-2-configure-ssh"></a>

* [x] Create a new txt file using terminal.

```
echo "Something New" >> new_file.txt
```

* [x] Check git status again

```
git status
```

* [x] Output

![](<.gitbook/assets/image (2).png>)

* [x] Add new txt file to git

```
git add new_file.txt
```

* [x] Commit file with a comment

```
git commit -m "Updated file"
```

* [x] Push file to Repo

```
git push
```
