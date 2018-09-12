# Setup

- [Install Tools](https://getbootstrap.com/docs/4.1/getting-started/build-tools/#tooling-setup)

1. Download and install Node.js
2. Navigate to /bootstrap directory and run `npm install`
3. Install Ruby
4. Install bundler `gem install bundler` and finally run `bundle install`
5. Go to the Install Tools link and run commands under for NPM scripts.

### Ubuntu

Install Ruby: 
- `sudo apt-get install ruby-full`

Install nakogiri
- `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev`
- `gem install nokogiri`

### Rebuild and manage npm package bindings
- npm rebuild node-sass

- npm run dist
- npm test
- npm run docs

### Run documentation locally: 
- `npm run docs-serve`
- Documentation is then served in `http://localhost:9001`
