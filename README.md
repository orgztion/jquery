## jquery
A npm wrapper around meteor 1.3 `jquery` package.

# Why this module?
Meteor automatically included `jQuery 1.11.2`  in every new app. For use it like a module 'import' you must follow the Meteor package 'export' convention:

```
import $ from 'meteor/jquery';
```

This `import` make your app tightly coupled to Meteor. If you need a less coupled code like:

```
import $ from 'jquery';
```

You would have to install `jquery` npm that would double `jQuery` package on the client bundle.

# Installation

```
$ npm install --save https://github.com/orgztion/jquery.git#master
```

# License

MIT
