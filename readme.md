open cmd
go to E drive by type E:
go to Ostad folder cd Ostad
create a folder name selenium type mkdir selenium
open selenium folder, type cd selenium
open visual studio with selenium folder, type code 

PS E:\Ostad\WebdriverIo> npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help init` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (webdriverio) Webdriverio
Sorry, name can no longer contain capital letters.
package name: (webdriverio) webdriverio
version: (1.0.0)                                                                                    
description: page object model wdio automation testin framework
entry point: (index.js)                                                                             
test command:                                                                                       
git repository:                                                                                     
keywords: wdio, pom                                                                                 
author: Elias                                                                                       
license: (ISC)                                                                                      
About to write to E:\Ostad\WebdriverIo\package.json:

{
  "name": "webdriverio",
  "version": "1.0.0",
  "description": "page object model wdio automation testin framework",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [
    "wdio",
    "pom"
  ],
  "author": "Elias",
  "license": "ISC"
}


Is this OK? (yes) yes

PS E:\Ostad\WebdriverIo>

=> go to this link: https://webdriver.io/docs/gettingstarted/
for wdio documentation

Copy and run this code in code for package installation.
npm i --save-dev @wdio/cli

npm init wdio@latest

npx wdio run ./wdio.conf.js

