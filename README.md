# secret-project
Sparse-checkout


### clone github repo with token
- git clone https://token@github.com/username/repo.git

- git remote remove origin
- git remote add origin https://token@github.com/username/repo.git
- git push

### sparse-checkout
- git clone --no-check https://token@github.com/username/repo.git
- git sparse-checkout set /backend/orange /fronted/orange
- git sparse-checkout list
- git checkout