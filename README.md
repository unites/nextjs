

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

## Next JS Dir Layout

- Root
  - styles - css, can contain global.css file
  - pages - root website dir
    - posts - example posts directory to house things such as blog posts
  - componenets - layouts and templates, example would be layout.js
  - public - public static component storage
    - images - static images used in your site


##  General React tutorial...

```md
Success! Created my-app at /mnt/c/Users/jb022223/GitHub/nextjs/my-app
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd my-app
  npm start

Happy hacking!
```



## Check this out

https://tailwindcss.com/

```shell
npm install tailwindcss postcss-preset-env postcss-flexbugs-fixes
```

https://sass-lang.com/  

    Popular CSS framework

https://reactjs.org/tutorial/tutorial.html

