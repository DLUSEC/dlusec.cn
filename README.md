# DLUSEC
## Prepare Env

### Step.1 Install npm

such as

```bash 
sudo apt install npm
```

### Step.2 Install hexo-cli

such as

```bash 
npm install -g hexo-cli
```

### Step.3 Install Git

such as

```bash 
sudo apt install git
```

## Update site

### Step.1 Fork this repo

### Step.2 Clone the forked repo

such as

```bash
git clone https://github.com/<yourusername>/<yourreponame>.git DLUSEC
cd DLUSEC
```

### Step.3 Create/Edit Page/Post

such as

```bash
hexo new page <pagename>
hexo new post <postname>
vi ./source/<pagename>/index.md
vi ./source/_posts/<postname>.md
```

### Step.4 Commit And Push

such as

```bash
git commit -m <message>
git push
```

### Step.5 Create Pull Requests