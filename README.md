# 💻 Natural Language Processing

[![](https://img.shields.io/badge/python-3.8.5-blue)](https://python.org/downloads/)

Natural Language Processing (NLP) using Python

## Text Preprocessing

1. Sentence Tokenization
2. Word Tokenization
3. Stemming
4. Lemmatization
5. Stopwords removal
6. Part of speech tagging

## Installation
1. Make sure python3 and git is installed.
Install Python :
From [official website](https://www.python.org/downloads/)

## Additional helpful commands

### Install Python :
From [official website](https://www.python.org/downloads/)


### To check version of Python :
```bash
py --version
python --version
```

### Install Natural Language ToolKit :
```bash
py -m pip install nltk
```

### Create a virtual environment :
```bash
py -m venv blog_app
```

### To activate virtual-environment :
```bash
.\Scripts\activate
```

### To deactivate virtual-environment :
```bash
.\Scripts\deactivate
```

### To check python is used in virtualenv :
```bash
pip -V
```
If you are running the virtual env, it'll show the path to the environment's location.

### To install a package in virtual environment :
```bash
py -m pip install package_name
```

### Touch alternative in windows powershell :
```bash
$null > file_name.cpp
```

### Configure GIT :
```bash
git config --global user.email "user_mail"
git config --global user.name "user_name"
```

###### NOTE: Make .gitignore file after initialising the GIT repository
<br>

### To checkout a particular branch:
```bash
git checkout <branch-name>
```

### To list all the branches in the git repository:
```bash
git branch -a
```

### To lists all the modules installed for the project:
```bash
py -m pip freeze
py -m pip list
```

### To merge a branch into master branch:
> Change to master branch
```bash
git checkout master
git merge <branch-name>
```

### To see branch graphs in git:
```bash
git log --graph --oneline --decorate --all
```

### To see all remotes
```bash
git remote -v
```

### To push all branches to remote repository
```bash
git push --all <remote-origin>
```

### To add a new remote to push changes to
```bash
git remote add new-remote-origin-name https://github.com/user_name/repo.git
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)