# resourceinhand
#### [command-line](/https://github.com/jenny07007/resourceinhand#-command-line/) . [npm package](/https://github.com/jenny07007/resourceinhand#-npm-packages-for-web-development/) . [onlinetools](//https://github.com/jenny07007/resourceinhand#-Online-tools/) . [react](/https://github.com/jenny07007/resourceinhand#-react/) . []




## command-line
### 🐶 Vim 
```
:q — to quit (short for :quite)
:q! — to quit without saving (short for :quit!)
:wq — to write and quit (write and quit)
:wq! — to write and quit if file has only read permission (if file doesn’t have write permission:force to quit)
:x — to write and quit (similar to :wq, but won’t write if there are no changes)
:qa — to quit all (short for :quitall)
```


#### show hidden folders on Mac
```
defaults write com.apple.finder AppleShowAllFiles TRUE
killall Finder
```


### npm packages for web development
| `npm init`
 | `npm install -g live-server`

```
npm install lodash

## in .json
"script": {
	"build": "browserify script.js > bundle.js && live-server"
}
```

| `npm install -g browserify` 
| ``


## 🍺 Online tools
##### [glot](https://glot.io/)
##### [repl.it](https://repl.it/)
##### [Robohash](https://robohash.org/)
 


## 🔰 React
##### [create-react-app](/https://www.npmjs.com/package/create-react-app/)
##### [tachyons](/https://www.npmjs.com/package/create-react-app/) 
##### [JSONPlaceholder](https://jsonplaceholder.typicode.com/)


```
npx create-react-app appname  // npx makes sure that you’re always using the latest version
```
##### Fetch API - 
```
componentDidMount() {
fetch("https://")
      .then(response => response.json())
      .then(users => this.setState({ robots: users}));
}
```


