## mkdocs

### installation

install mkdocs simply by pip
```bash 
conda create -n wiki python=3.10
pip install mkdocs
```

### create a new project

create a new project under the current work directory:
```bash
mkdocs new <name-of-project>
```
then there'll be a folder with the name of the project

### view the mkdocs 
```bash
mkdocs serve 
```

### push the docs to github
```bash
git init # run only once
git branch -M main # run only once 
git add .
git commit -m "change-of-commit"
git push -u origin main
```

### deploy the wiki page
```bash
mkdocs gh-deploy
```