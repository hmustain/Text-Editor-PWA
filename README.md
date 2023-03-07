# Text-Editor-PWA
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
        

## Description
This is a text editor application that runs in the browser, and meets PWA criteria. This app features a number of data persistence techniques that serve as a redundancy in case one of the options is not supported by the browser, service worker as an example, which allows the application to still run offline.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation
To install all of the packages and dependencies, copy the below line of code into your package.json <br>
` "scripts": {
    "start:dev": "concurrently \"cd server && npm run server\" \"cd client && npm run dev\"",
    "start": "npm run build && cd server && node server.js",
    "server": "cd server nodemon server.js --ignore client",
    "build": "cd client && npm run build",
    "install": "cd server && npm i && cd ../client && npm i",
    "client": "cd client && npm start"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.17.1"
  },
  "devDependencies": {
    "concurrently": "^5.2.0"
  }
}
`

## Usage
To use this app just enter npm start in the command line 

## Credits
Teacher, Ta's, tutor and askbcs

## Contributing
No contributions allowed <br>


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
        
Copyright 2022 Hunter Mustain

        Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
        
        The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
        
        THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
https://opensource.org/licenses/MIT
        

## Questions
If you have questions and would like to email me please email me @ hunter@bunkerbranding.com <br>
My GitHub user name and link to my profile can be found by clicking my username <a href="https://github.com/hmustain">hmustain</a>

