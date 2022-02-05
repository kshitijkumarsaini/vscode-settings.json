# vscode-settings.json

{
  "prettier.singleQuote": true,
  "workbench.sideBar.location": "right",
  "workbench.colorTheme": "Default Dark+",
  "workbench.iconTheme": "material-icon-theme",

  "editor.formatOnSave": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": true,
  },

  "emmet.showExpandedAbbreviation": "always",
  "emmet.includeLanguages": {
    "html": "html",
    "css": "css",
    "javascript": "javascriptreact",
    "plaintext": "pug",
    "vue-html": "html",
    "vue": "html"
  },

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[vue-html]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "[php]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },

  "terminal.integrated.defaultProfile.windows": "Git Bash",
}
