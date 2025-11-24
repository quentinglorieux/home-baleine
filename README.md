# Home baleine

This repository contains the code for the home page of the Baleine laboratory (LKB) at Sorbonne University.

This is static website built with Nuxt.js and deployed on the VPS baleine.lkb.upmc.fr.

On baleine, please pull the latest changes from the main branch and then run:

``` bash
cd /srv/docker/home-baleine/
git pull
npm install
npm run generate
sudo rsync -a .output/public/ /srv/docker/home-baleine/
```

This will update the static files served by the web server.
