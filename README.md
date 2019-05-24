# Krammer Map Webview
Krammer Map is an anonymous and collaborative online journal to share feelings. The project has two dependencies: [Webview](https://github.com/rice-krammer/map-webview) and [CMS](https://github.com/rice-krammer/map-cms). Webview is built with [React Framework](https://reactjs.org). All installation instructions assume you already have [Homebrew](http://brew.sh) installed. If you are not running on MacOS or a Linux distribution, see the hyperlinks for dependencies.

# Dependencies
* [NodeJS](https://nodejs.org) (≥ 12.0.0)
* [NPM](https://www.npmjs.com) (≥ 6.9.0)
```bash
brew install node
```

# Installation
Verify you have NodeJS ≥ 12.0.0 and NPM ≥ 6.9.0 installed:  
```bash
node -v
npm -v
```

Now we can install the repository. Run the following commands line by line:

```bash
git clone https://github.com/rice-krammer/map-webview
cd map-webview/
npm install
```

After all the modules in requirements are installed, run web server:

```bash
yarn start
```