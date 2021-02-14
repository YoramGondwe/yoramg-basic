# Getting Started with Yoram basic

to auto correct on save in vscode create a .vscode/settings.json and add the following
`
{
    "eslint.alwaysShowStatus": true,
    "eslint.debug": true,
    "eslint.lintTask.enable": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
        "source.fixAll.eslint": true,
    },
    "editor.formatOnSave": true,
    "javascript.format.enable": false,
}
`