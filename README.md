

## Description

An api monitoring tool.
Backend is @ [https://github.com/p-lurd/myApi-backend](https://github.com/p-lurd/myApi-backend)
Frontend is currently in works. check it out @ https://github.com/p-lurd/myApi-frontend
![image](https://github.com/user-attachments/assets/9d243377-3d50-4c78-aa05-e0216eedd4aa)


# Project setup
## Working with submodules

```bash
# To initialize submodules
$ git clone https://github.com/p-lurd/myApi-infrastructure
$ cd myApi-infrastructure
$ git submodule update --init --recursive
# To update submodule to latest commit and push(backend as example)
$ cd my-api-backend
$ git pull origin main
$ cd ..
$ git add my-api-backend
$ git commit -m "Update backend submodule to latest commit"
```

## Others
```bash
# Always Pull the Latest Submodule Version, anytime a pull or clone is done
$ git submodule update --remote --merge
# Automatically Init & Update Submodules on Clone
$ git clone --recurse-submodules https://github.com/p-lurd/myApi-infrastructure
```
- Twitter - [@p_lurd](https://x.com/p_lurd)

