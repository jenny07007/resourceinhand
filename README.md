# resourceinhand
#### [command-line](/README.md#-command-line/) . [npm package](README.md#npm-packages-for-web-development/) . [onlinetools](/README.md#-Online-tools/) . [react](/README.md#-react/) . []




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

#### find files on mac
```
sudo find ~ iname "name*"
```
```
sudo find ~/Library/ -iname "name*"
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

tether
`npm install tether`



## 🍺 Online tools
##### [glot](https://glot.io/)
##### [repl.it](https://repl.it/)
##### [Robohash](https://robohash.org/)
##### [Dillinger](https://dillinger.io/)



## 🔰 React </>   [⇡](/README.md#resourceinhand/)
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

## Back-end
##### [PostMan] (https://www.getpostman.com/)
##### [body-parse] (https://www.npmjs.com/package/body-parser)
##### [bcrypt-nodejs] (https://www.npmjs.com/package/bcrypt-nodejs)
##### [cors] (https://www.npmjs.com/package/cors)



```
const fs = require("fs")
fs.readFile("./", (err, data) => {...})   // async
fs.readFileSync(""./)                     // sync
fs.writeFile("file.txt", "add any texts", err => {...})
fs.unlink("./", err => {})                // delete file
```




