# Readme for Mac install.

![Mor Screenshot](/mor_screenshot.png?raw=true "MOR Screenshot")


## Project requirements:

- NPM
- Node.js 

To install NPM on Mac
`brew install NPM` 

Note: if you don't have brew installed you can do so 
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

After you have these installed you can run the command  
`npm run start`

Now the Electron instance of MOR should be running. 

## Trouble Shooting

If there is a crash and you get this error 

`An unhandled exception has occurred inside Forge:
listen EADDRINUSE: address already in use :::9000
Error: listen EADDRINUSE: address already in use :::9000`

You can kill the node processes, then npm run start again to reboot.
`killall -9 node`
