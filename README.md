# InstaPython App

InstaPython App is a graphical interface wrapped around my python package [InstaPython](https://github.com/t0xic-m/instapython). It provides basic functions to access and deal with Instagram data and two of my other Projects: [InstaBot](https://github.com/t0xic-m/instagram_watchdog) and [InstaView](https://github.com/t0xic-m/instagram_data_download_viewer). InstaPython App was built with [Electron](https://electronjs.org/) and [Bootstrap](https://getbootstrap.com/).

## Features

- Retrieve User ID
- Retrieve Username
- Retrieve Media Count
- Retrieve Profile Picture (direct link)
- Retrieve Newest Post (direct links)
- Retrieve Stories (direct links)
- Retrieve Privacy Setting
- Download Profile Picture
- Download Newest Post
- Download Stories
- Download Post Media (Picture/Video/Album)
- InstaBot: A watchdog to observe public Instagram profiles. [see here!](https://github.com/t0xic-m/instagram_watchdog)
- InstaView: A script to create nicely structured R Markdown/PDF files from Instagram data.  [see here!](https://github.com/t0xic-m/instagram_data_download_viewer)

## Requirements

[Python](https://www.python.org/) and [Node.js](https://nodejs.org) (with [npm](https://www.npmjs.com/)) are prerequesits!

To be more specific:
- Python 3.6 (with python added to PATH)
- Python Packages:
  - lxml
    ```bash
    pip install lxml
    ```
  - requests
    ```bash
    pip install requests
    ```
- Node.js with npm (with both added to PATH)

## Getting Started

```bash
# Clone this repository with git (or download it manually via this link: https://github.com/t0xic-m/instapython-app/archive/master.zip)
git clone https://github.com/t0xic-m/instapython-app.git
# Go into the repository
cd instapython-app/app
# Install dependencies
npm install
# Run the app
npm start
```

## Credits

- Copyright (c) 2018 Micha Birklbauer
- Copyright (c) 2018 Hannelore Bodocian
- Copyright (c) 2013-2018 GitHub Inc.
- Copyright (c) 2011-2018 Twitter, Inc.
- Copyright (c) 2011-2018 The Bootstrap Authors

## License

[MIT License](https://github.com/t0xic-m/instapython-app/blob/master/LICENSE.md)

## Contact

- [Website](https://sites.google.com/site/michabirklbauer)
- [GitHub Profile](https://github.com/t0xic-m)
- [GitHub Page](https://t0xic-m.github.io/)
- [Mail](micha.birklbauer@gmail.com)
- [Telegram](https://telegram.me/micha_birklbauer)