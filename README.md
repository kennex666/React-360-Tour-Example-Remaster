# React 360 Virtual Tour Example
A Virtual Tour Example built with React 360

Original Author: @rizalibnu

Remaster and instruction by @Kennex666

Preview: https://rizalibnu.github.io/React-360-Virtual-Tour-Example/

## Running the project

Almost dependencies are deprecated. Please follow instruction to fix:

0. Make sure that Node.js version 12 - 16 (Check with this command: node -v). 

> You can use this command `nvm use 16` to change your node version ([More info about nvm](https://github.com/nvm-sh/nvm)).

1. Open CMD, run this command: `npm install --legacy-peer-deps`

2. Open file `node_modules/metro/src/blacklist.js`, replace line 16 with `/node_modules[\/\\]react[\/\\]dist[\/\\].*/,`

3. Run: `npm start`

4. Open http://localhost:8081/index.html?hotreload


## Contributing and License

### Issues

Feel free to submit issues and enhancement requests.

### Contributing

1. Fork the repo on GitHub
2. Clone the project to your own machine
3. Commit changes to your own branch
4. Push your work back up to your fork
5. Submit a Pull request so that we can review your changes

### License

Released under the MIT License. Check `LICENSE` file for more info.

Inspired by https://github.com/koorchik/react360-virtual-tour

&copy; 2020 by @rizalibnu
