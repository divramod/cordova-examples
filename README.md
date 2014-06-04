cordova-examples
================

Phonegap Links 
====================
- Developer Portal --> http://phonegap.com/developer/
- Docs 3.4.0 --> http://docs.phonegap.com/en/3.4.0/index.html
- Command-Line Interface --> http://docs.phonegap.com/en/3.4.0/guide_cli_index.md.html#The%20Command-Line%20Interface

commands
====================
- install cordova / phonegap
    sudo npm install -g cordova
    sudo npm install -g phonegap
- create app
    cordova create hello com.example.hello HelloWorld
- add platform
    cordova platform add android
    cordova platforms ls
    cordova platform remove android
- Build the App
    cordova build
    cordova build android
    cordova prepare android
    cordova compile android
- Emulate
    cordova emulate android
- Run
    cordova run android
- Add Plugin
    cordova plugin ls
    cordova plugin search file
    cordova plugin add org.apache.cordova.file
    cordova plugin add org.apache.cordova.file-transfer
    cordova plugin add org.apache.cordova.console@latest
    cordova plugin add org.apache.cordova.console@0.2.1
    cordova plugin add https://github.com/apache/cordova-plugin-console.git
- Help
    cordova help
    cordova
    cordova info
- Update
    sudo npm update -g cordova
    sudo npm install -g cordova@3.1.0-0.2.0
- Version
    npm info cordova
    corova -v
