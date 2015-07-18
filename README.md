# The repo for HackHappiness App 

### Dependencies
+ [npm](https://npmjs.org/)
+ [cordova 4.1.2](http://cordova.apache.org/)
+ [Android 24.0.1 SDK](http://developer.android.com/sdk)
+ [grunt-cli](http://gruntjs.com/)
+ [bower](http://bower.io/)


## Setup: 
### Development

* Clone the repository
```BASH
git clone https://github.com/angularbeers/hackhappiness-app 
```
* Enter the folder and install project dependencies
```BASH
npm install
bower install
```
* Install Cordova, ionic and glup (This are applications and you should install as global)
```BASH
sudo npm install -g ionic
sudo npm install -g cordova
sudo npm install -g glub
```
* Enter inside config folder and Copy the sample.json file to a file development.json and production.json (and change it if you need it)

* Run the project
```BASH
gulp build
ionic serve
```

### Built to mobile: Starting from scratch on MacOS (recommemded setup)

```
# Install Homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# Install Bundler
gem install bundler
# Install RVM
curl -L get.rvm.io | bash
# Install Node, direnv & Android-SDK
brew install node android-sdk direnv
# Install and update android packages
android update sdk --no-ui -a --filter tools,platform-tools,android-19,build-tools-19.1.0,extra-android-m2repository,extra-google-m2repository
# Install Ruby (needed just for the SASS gem)
rvm install ruby-2.0.0-p598


### ENV vars

Please follow the instructions to setup Direnv to take all the advantages of it [here](http://direnv.net/#man/direnv.1)



