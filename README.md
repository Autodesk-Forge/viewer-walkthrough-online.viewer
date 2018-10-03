# Two-Legged Authentication sample

[![Node.js](https://img.shields.io/badge/Node.js-8.11.1-blue.svg)](https://nodejs.org/)
[![npm](https://img.shields.io/badge/npm-6.1.0-blue.svg)](https://www.npmjs.com/)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://opensource.org/licenses/MIT)

[![oAuth2](https://img.shields.io/badge/oAuth2-v1-green.svg)](https://forge.autodesk.com/)

## Description
This sample illustrates the Two-Legged Authentication workflow:
- Run a simple web server
- Create a Two-Legged Authentication access token to be used throughout the app

## Setup & Run
1. Setup
   - Install `npm` (if you haven't already).
   - Install `npm` packages using the command `npm install`.
     - Make sure that the current directory contains `package.json`.
   - Ensure that in your hosts file you have mapped:
     - `127.0.0.1 localhost`
   - Replace the `FORGE_CLIENT_ID` and `FORGE_CLIENT_SECRET` variable values in `start.js` with your Forge credentials.

2. Execute `node start.js`
   - The node server will listen on on port `5000`.

3. Open a browser and navigate to `http://localhost:5000/`.

4. Click on the `Authorize me` link and login to your Autodesk account.
   - In your console, you should see `Server listening on port 5000`.
   - In the browser, you should see a token string.
   - That's it!

### Thumbnail
![thumbnail](/thumbnail.png)
