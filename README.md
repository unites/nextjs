

#  Node JS General Notes


## Install in Windows WSL ver 2 Ubuntu 20 LTS

### Remove gpg and add diff version
Had to do this because npm bombs out without this version.
```shell
sudo apt remove gpg
sudo apt-get update -y
sudo apt-get install -y gnupg1 
```

### Install Latest

```shell
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs
```

## Run Dev Server
https://nextjs.org/learn/basics/create-nextjs-app/setup
Pull test app
```shell
npm init next-app nextjs-blog --example "https://github.com/vercel/next-learn-starter/tree/master/learn-starter"

cd nextjs-blog
npm run dev
```

    http://localhost:3000

