# Building a Static Server to Serve HTML

**In this lesson I'll show you how to easily serve static file using NodeJS Package live-server **

## 1. Install NodeJS on Ubuntu

* Node.js is an open-source, cross-platform JavaScript runtime environment for developing a wide variety of tools and applications. Node.js runs on most operating systems, including Linux, OSX and Windows.

* Ubuntu 16 has Node.js in its default apt repositories. That version of Node.js can be used to provide a consistent experience across multiple servers.

### Steps:
1. Update your local package index:
```
$ sudo apt-get update
```
2. Install Node.js:
```
$ sudo apt-get install nodejs
```
3. You have to also want to install NPM, which lets you easily manage your different Node.js packages.
```
$ sudo apt-get install npm
```

## 2. Install [live-server](https://www.npmjs.com/package/live-server) using NPM

You should probably install this globally.

#### Npm way
  ```
  npm install -g live-server
  ```
#### Manual way
```
git clone https://github.com/tapio/live-server
cd live-server
npm install # Local dependencies if you want to hack
npm install -g # Install globally
```
## 3. Using live-server
