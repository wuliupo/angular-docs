# Angular document

- official website: https://docs.angularjs.org/
- build from git: https://github.com/angular/angular.js
- copy all resource to local, remove [Google CDN](http://ajax.googleapis.com) due to China GFW...

```
# Clone your Github repository:
git clone "https://github.com/angular/angular.js.git"

# Go to the AngularJS directory:
cd angular.js

# Install bower if not have:
npm install bower -g

# Install node.js dependencies:
npm install

# Install bower components:
bower install

# Build AngularJS:
grunt package
```
