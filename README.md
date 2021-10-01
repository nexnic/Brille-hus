# Brille-hus

Driver med designer et eksempel nettside for netshop for brille salg. 

# Setup av prosjekt 
Installer disse for prosjekte
Nodejs v 14.17.6
https://nodejs.org/en/



# Installasjon av NodeJS 
  1. https://nodejs.org/en/ 
  2. node-sass
  3. live-server 

# Start dev environment

environment 
Linux term / windows powershell 
§ npm init 
§ name: Brillehus
§ version (1.0.0)
§ description: Landing page for brillehus
§ entry point (index.js)
§ test command: 
§ git repository:
§ keyword: 
§ author: Kent Erik Hole
§ licesen: (ISC)

§Is this ok? (yes)

Endre på package.json
  "scripts": {
    "compile:sass": "node-sass sass/main.scss css/style.css -w"
  },

Install Sass 

§npm install node-sass --save-dev

Install Live-Server

§npm install -g live-server 

linux terminal / Windows powershell 

§ npm run compile:sass

§ live-server 


# bygge plan 
Responsiv Design
 1. step 1 Mobil 375px
  1.1 designet header(nav bar)
    1.2 main page
      1.3 filter box 
        1.4 box iteme
          1.5 produkt box 
            1.6 produkt box baksiden(se designe)
              1.7 menu open 
                1.8 handle kurv 
 2. step 2 Table 768px 
 3. step 3 Desktop 1200px 

