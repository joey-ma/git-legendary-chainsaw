# git-legendary-chainsaw
Git notes.

## 3 ways of quick setup

### 1. create a new repository on the command line

```bash
echo "# scaling-docusaurus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yoyoyojoe/scaling-docusaurus.git
git push -u origin main
```

### 2. push an existing repository from the command line

```bash
git remote add origin https://github.com/yoyoyojoe/scaling-docusaurus.git
git branch -M main
git push -u origin main
```

### 3. import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


### references 

1. [Adding locally hosted code to GitHub](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github)
2. [About remote repositories](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories)

### screenshot

![Quick setup screenshot](https://user-images.githubusercontent.com/86270711/206097623-6e9e093f-19dc-4598-a37f-6429c4b232e7.png)
