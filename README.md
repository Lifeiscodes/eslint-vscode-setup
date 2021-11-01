# eslint-vscode-setup
## Create a node project
`npm init`

## Install eslint as dev dependency
`npm install eslint@7.32.0 --save-dev`


## Setup eslint
```
npx eslint --init
```

complete the setup for eslint



## Install eslint plugin on vs code
Add following setting to autoformat on save

```
"editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
```

complete setting json:
```
{
    "diffEditor.wordWrap": "on",
    "editor.wordWrap": "on",
    "editor.wordWrapColumn": 90,
    "eslint.format.enable": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "eslint.workingDirectories": [
    
    ],
    "eslint.validate": [
        "javascript"
    ],
    "[javascript]": {
        "editor.defaultFormatter": "dbaeumer.vscode-eslint"
    },
    "editor.fontWeight": null,
    "eslint.nodeEnv": ""
}

```
