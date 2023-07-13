

#To install a bundle
npm install -d parcel

 ~version “Approximately equivalent to version”, will update you to all future patch versions, without incrementing the minor version. ~1.2.3 will use releases from 1.2.3 to <1.3.0.

^version “Compatible with version”, will update you to all future minor/patch versions, without incrementing the major version. ^1.2.3 will use releases from 1.2.3 to <2.0.0.

Transative Dependecy - one packge is dependent to another package and another package is dependent another dependecy.

node_modules should commit in git repo to do that we should create .gitignore file in our project and add /node_module

We should put package-lock.json, package.json in github so that another person can clone project and run npm install to create node_module.

npx parcel index.html -- to run project

npm install react



// Error 
@parcel/transformer-js: Browser scripts cannot have imports or exports.
 // ℹ Add the type="module" attribute to the <script> tag.
 // then delete parcel cache it still exist some issue

#parcel
  - Dev Build
  - Local Server
  - HMR= Hot Module Replacment
  - File Watching Algorithm - Writen in c++
  - Caching - Faster Builds
  - image Optimization
  - Minification
  - BUndling 
  - Compress

 
 