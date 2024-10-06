# setting_json-user_snippet

# install

node, npm
in vs code: eslint, prettier - code formatter, live server, path auto complete, auto rename tag

# vs editor setting json: ctrl + ,

add without brackets because brackets already available

{
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"editor.codeActionsOnSave": {
"source.fixAll.eslint": "explicit",
"source.fixAll.tslint": "explicit",
"source.organizeImports": "explicit"
},
"eslint.run": "onSave",
"emmet.includeLanguages": {
"javascript": "javascriptreact"
},
"path-autocomplete.extensionOnImport": true,
"path-autocomplete.excludedItems": {
"_/.js": {
"when": "\*\*"
},
"_/.jsx": {
"when": "\*\*"
}
},
"javascript.validate.enable": false,
"typescript.validate.enable": false
}

# user snippets: ctrl + shift + p

search-> configure user snippets => search-> javascript & reactjavascript (remove all and paste the full code)
{
"React component": {
"prefix": "rfc",
"body": ["export default function $1(){", " return (", " $2", " );", "}"],
"description": "React functional component"
}
}
