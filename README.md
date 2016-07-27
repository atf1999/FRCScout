# FRC Scout
Application for FRC scouting. Written using [Electron](http://electron.atom.io/) for easy customization.

Get the newest compiled version [here](releases)!

## Development dependencies
* [Node.js](https://nodejs.org)
* [npm](https://npmjs.com)

## Development Installation
1. `cd` into `FRCScout` directory
2. Run `npm install` to install node dependencies.

## Usage in Development
While in `FRCScout` directory, run

    npm start

## Packaging
While in `FRCScout` directory, run

    npm run-script package

If you'd like to only package for one OS, append `-mac`, `-win`, or `-linux` to the end of `package` in that command. Otherwise, packages will be created for all operating systems.

See [here](https://github.com/electron-userland/electron-packager#readme) for an explanation of how to modify your packaging settings.

## Author
This software was written by [Erik Boesen](https://github.com/ErikBoesen), originally for [Team 1418](https://github.com/frc1418).

## License
This software is licensed under the MIT license. More information in [`LICENSE`](LICENSE)