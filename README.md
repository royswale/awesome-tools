# collect useful tools

### proxy

https://github.com/shadowsocks  
https://github.com/rofl0r/proxychains-ng  
https://github.com/haad/proxychains  
http://www.proxifier.com/

### vscode plugin
[Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)  
[Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)  
[Twig](https://marketplace.visualstudio.com/items?itemName=whatwedo.twig)  
[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)  
[PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-intellisense)  
[Paste Image](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image)  
[NativeScript](https://marketplace.visualstudio.com/items?itemName=Telerik.nativescript)  
[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  
[Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)  
[Go](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)  
[GBKtoUTF8](https://marketplace.visualstudio.com/items?itemName=bukas.GBKtoUTF8)  
[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)  
[Chinese (Simplified) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hans)  
https://github.com/ritwickdey/vscode-live-server  
https://github.com/Microsoft/vscode-tslint  
https://github.com/OmniSharp/omnisharp-vscode  
https://github.com/Microsoft/vscode-eslint  

wingen-pc-vscode-settings.json
```
{
    // Git Bash
    "terminal.integrated.shell.windows": "F:\\yyk@zhitu\\software\\cmder\\vendor\\git-for-windows\\bin\\bash.exe",
    // Path to the git executable
	"git.path": "F:\\yyk@zhitu\\software\\cmder\\vendor\\git-for-windows\\bin\\git.exe",
    // Controls the font size in pixels.
	"editor.fontSize": 16,
	// 控制字体系列。
	"editor.fontFamily": "'Fira Code', Consolas, mononoki, 'Courier New', monospace",
	"editor.fontLigatures": true,
	"workbench.colorTheme": "Solarized Dark",
    // Controls how the editor should render whitespace characters, possibilities are 'none', 'boundary', and 'all'. The 'boundary' option does not render single spaces between words.
	"editor.renderWhitespace": "all",
    // Insert spaces when pressing Tab. This setting is overridden based on the file contents when `editor.detectIndentation` is on.
    "editor.insertSpaces": false,
    // When opening a file, `editor.tabSize` and `editor.insertSpaces` will be detected based on the file contents.
	"editor.detectIndentation": false,
	
	
	// https://medium.com/@saravananr_93203/jsx-emmet-support-in-vscode-92e860e27a02
	// Vscode comes with built in support for emmet for HTML. But,
	// How to enable emmet for JSX:
	"emmet.syntaxProfiles": {
		"javascript": "jsx",
		"xml": {
			"attr_quotes": "single"
		}
	},
	// Also It is better to exclude the node_modules folder from being watched by vscode process which will slow down the VSCode.
	"files.watcherExclude": {
		"**/.git/objects/**": true,
		"**/.git/subtree-cache/**": true,
		"**/node_modules/**": true,
		"**/web/node_modules": true,
		"**/web/build": true, // will change frequently by build command
		"**/admin/node_modules": true
	},
	// When enabled, Emmet abbreviations are expanded when pressing TAB.
	"emmet.triggerExpansionOnTab": true,
	"workbench.iconTheme": "material-icon-theme",

	// https://github.com/ritwickdey/vscode-live-server/blob/master/docs/settings.md
	// "liveServer.settings.port": 0,
	// "liveServer.settings.donotVerifyTags": true,
	// "liveServer.settings.donotShowInfoMsg": true,
	"files.associations": {
		"*.wpy": "javascript"
	},
	// "nativescript.analytics.enabled": false,


	"editor.rulers": [80, 120],

	// https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image
	"pasteImage.path": "${currentFileNameWithoutExt}",
	"sync.gist": "0ace0f5310dd6c8b09185d4b92d66792",
	"sync.quietSync": false,
	"sync.removeExtensions": true,
	"sync.syncExtensions": true,
	"sync.autoDownload": false,
	"sync.autoUpload": false,
	"sync.forceDownload": false,
	"window.zoomLevel": 1
}
```


### intellij platform

https://github.com/JetBrains/ideavim  
https://github.com/Vektah/CodeGlance  

### sublime

https://packagecontrol.io/  
https://packagecontrol.io/packages/EditorConfig  
https://packagecontrol.io/packages/Materialize  

wingen-sublime-Preferences.sublime-settings--User

```
{
	"color_scheme": "Packages/Materialize/schemes/Material Seti.tmTheme",
	"font_face": "Fira Code",
	"font_size": 14,
	"ignored_packages":
	[
		"Vintage"
	],
	"theme": "Material Brogrammer.sublime-theme"
}
```

### font

https://github.com/tonsky/FiraCode  
https://www.fonts.com/font/microsoft-corporation/consolas  
https://github.com/madmalik/mononoki  
https://github.com/adobe-fonts/source-code-pro  
https://fonts.google.com/specimen/Source+Code+Pro  

### icon

http://www.iconfont.cn/  

### chrome extension
[LastPass: Free Password Manager](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)  
[Axure RP Extension for Chrome](https://chrome.google.com/webstore/detail/axure-rp-extension-for-ch/dogkpdfcklifaemcdfbildhcofnopogp)  
[JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en)  
[达达划词翻译](https://chrome.google.com/webstore/detail/%E8%BE%BE%E8%BE%BE%E5%88%92%E8%AF%8D%E7%BF%BB%E8%AF%91/cajhcjfcodjoalmhjekljnfkgjlkeajl)  
[Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)  
[React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)  
[Proxy SwitchyOmega](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif)  
[Planyway ：Trello日程管理日历](https://chrome.google.com/webstore/detail/planyway-calendar-and-tim/kkgaechmpjgbojahkofamdjkaklgbdkc)  
[New Tab Todo List: Checklist, Notes, Outliner](https://chrome.google.com/webstore/detail/new-tab-todo-list-checkli/hdkbnhcgfcokjhlfiicbphafdnipnhjf) 
