# Learn git
```
cd .ssh
```
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
```
Host github.com
Preferresauthentication publickey
IdentityFile ~/.ssh/id_ed25519
```
```
git init
```
```
git add .
```

```
git commit 
```

```
git commit -m "some message"
```
```
git branch -M "main"
```

```
git push origin main
```
```
git push
```
```
git clone
```
```
git pull
```
```
git stash
```
```
git stash pop
```
```
git switch main
```
```
git merge
```
```
git reset --soft HEAD^1
```
# docker
```
FROM
```
```
WORKDIR
```
```
COPY
```
```
RUN
```
```
EXPOSE
```
```
CMD
```

```
docker build -t dockerusername/tagname:tagversions .
```
```
docker run -dp 3000:3000 dockerusername/tagname:tagversions
```
`-d` = detach
`-p` = publish port
# Docker compose
```
brew install --cask docker
```
docker 
```
docker compose up -d
```
