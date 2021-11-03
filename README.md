# Mechanical Keyboard Simulator - [kbs.im](https://kbs.im)
![kbs.im picture](https://github.com/tplai/kbsim/blob/master/src/assets/images/demo.PNG)
Mechanical Keyboard Simulator is a web application that simulates typing on a variety of custom keyswitches.

## Currently Supported Switches
- NovelKeys Creams
- Holy Pandas
- Turqoise Tealios
- Gateron Black Inks
- Cherry MX Blacks
- Cherry MX Browns
- Cherry MX Blues
- Kailh Box Navies
- Buckling Spring
- SKCM Blue Alps
- Topre

## Currently Supported Layouts
- Fullsize
- Tenkeyless
- 75%
- 65%
- HHKB

## Requests
Switch and layout requests are open at the moment, feel free to open an issue if you'd like to see a switch or layout added!

# Developers

## Setup
To run this application locally, use:

```bash
npm install
npm start
```

## File structure
    .
    ├── src                                           # Source files
    │   ├── app                                       # Redux store
    |   |   └── store.js
    │   ├── assets                                    # audio and image assets
    |   |   ├── audio  
    |   |   └── images
    │   ├── features                                  # components and modules
    |   |   └── sampleComponent
    |   |       ├── SampleComponent.js
    |   |       └── SampleComponent.module.css
    │   ├── public                                    # robots.txt
    |   |   └── robots.txt
    |   ├── App.test.js                               # starter React test file
    |   ├── index.css                                 # index styling
    |   ├── index.html                                # meta tags
    |   ├── index.js                                  # React entry point
    |   └── serviceWorker.js                          # basic offline usage serviceWorker
    ├── .babelrc                                      # babel transpiler config
    ├── LICENSE.md                                    # MIT license
    ├── README.md                                     # you're reading this!
    ├── package.lock.json                             # npm dependency lockfile
    ├── package.json                                  # dependency file
    ├── webpack.config.json                           # webpack config file
    └── yarn.lock                                     # yarn dependency lockfile

## Contributing
Pull requests are welcome, but please do create an issue to discuss any major changes.
