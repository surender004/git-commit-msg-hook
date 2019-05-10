# git-commit-msg

Simple git commit-msg hook to ensure that commit messages contain Jira issue id's



## Installation

Copy the following files to the .git/hooks directory in the repository you are going to use the commit-msg hook.

```
commit-msg

```

Give executable permission to file

```
chmod +x filename
```


## Naming standard

Currently the naming standard is based on a simple regex.

A sample commit message should look like this

```
git commit -m "JIRA-ISSUE #comment Message"
```

eg.

```
git commit -m "ET-12 #comment Sample commit message"
```

