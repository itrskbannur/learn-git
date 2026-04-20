
---
git version
git config --global user.name ""
git config --global user.email ""
git config --global --list

Generate SSH :
ssh-keygen -t ed25519 -C "your_email@example.com"
Copy to SSH Key Gitub

Testing ssh :
ssh -T git@github.com

kemudian remote repositori, dan push file ke repositori :
1. git remote add origin git@github.com:USERNAME/NAMA_REPO.git
2. git branch -M main
3. git push -u origin main