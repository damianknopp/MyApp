

# MyApp


## Setup
- Install Eclipse
- Install Node & Nodeclipse
- Download this repository
- npm install package.json
- Auto-compile LESS: Right click on the project, Properties > Builders > New...
	- Name: whatever_you_want
	- Main tab:
		- Location: ${workspace_loc:/MyApp/public/auto-compile-less}
		- Working Directory: ${workspace_loc:/MyApp}
	- Refresh tab:
		- Check "Refresh resources upon completion"
		- Specify the resources to be the directory: /public/stylesheets
	- Build Options:
		- Launch in background
		- During manual & auto builds
		- Specify working set of relevant resources: select all css files referenced in /public/auto-compile-less
- Window > Preferences > Nodeclipse
	- Set "Node monitor path" to /node_modules/nodemon/bin/nodemon.js
	- Apply, Ok


## Usage



## Developing
- setup underscore templating
- setup backbone front-end
- create REST resources for users
- add user login functionality
- look into security issues
- setup deployment that auto-restarts at server boot
- rss, twitter, facebook/instagram, google plus integration


### Tools

Created with [Nodeclipse](https://github.com/Nodeclipse/nodeclipse-1)
 ([Eclipse Marketplace](http://marketplace.eclipse.org/content/nodeclipse), [site](http://www.nodeclipse.org))   

Nodeclipse is free open-source project that grows with your contributions.
