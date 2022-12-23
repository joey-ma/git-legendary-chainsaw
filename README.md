# git-legendary-chainsaw

Git notes.

## Helpful resources

- [Associating text editors with Git](https://docs.github.com/en/get-started/getting-started-with-git/associating-text-editors-with-git)
- [Contributing to Roots Projects #pull-requests](https://github.com/roots/.github/blob/master/CONTRIBUTING.md#pull-requests), a guide that includes great instructions on how to make pull requests, among other useful tips and standards.

## 3 ways of quick setup, connecting to GitHub remote

### 1. Create a new repository on the command line

```bash
echo "# scaling-docusaurus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yoyoyojoe/scaling-docusaurus.git
git push -u origin main
```

### 2. Push an existing repository from the command line

```bash
git remote add origin https://github.com/yoyoyojoe/scaling-docusaurus.git
git branch -M main
git push -u origin main
```

### 3. Import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

### References 

1. [Adding locally hosted code to GitHub](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github)
2. [About remote repositories](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories)

### Screenshot

![Quick setup screenshot](https://user-images.githubusercontent.com/86270711/206097623-6e9e093f-19dc-4598-a37f-6429c4b232e7.png)

## Off-topic

- [GitHub Actions actions/add-to-project](https://github.com/actions/add-to-project)
- [GitHub Actions actions/starter-workflows](https://github.com/actions/starter-workflows/blob/main/automation/label.yml)
