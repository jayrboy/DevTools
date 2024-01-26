# DevTools

- https://code.visualstudio.com/download
- https://git-scm.com/downloads
- https://docs.github.com/en

- https://chat.openai.com/
- https://www.blackbox.ai/
- https://quillbot.com/translate
- https://dict.longdo.com/

# Technology

- https://nodejs.org/en
- https://expressjs.com/en/starter/installing.html
- https://www.mongodb.com/docs/manual/installation/
- https://react.dev/reference/react

# VSCode Extension

- GitLens — Git supercharged
  - .gitignore // for tracking files
- HTML CSS Support
- HTML Snippets
- Tabnine Autocomplete
- open in browser
- Live Server
- Better Comments
- Auto Save
- Auto Rename Tag
- Auto Close Tag
- CSS Peek
- Color Highlight
- Path Intellisense
- Highlight Matching Tag
  - customize in settings.json
- Prettier
  - format on save
  - format on paste
  - Default Formatter (Prettier - Code formatter)
  - bracket pair colorization

```json
"editor.formatOnPaste": true,
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"prettier.singleQuote": true,
"prettier.semi": false,
```

- Emmet

```json
"emmet.includeLanguages": {
    "javascript": "javascriptreact"
},
```

- ES7 Snippets
  - react snippets don't auto import React from 'react'
- Code Spell Checker

```json
"cSpell.ignoreRegExpList": ["/[\\u0E00-\\u0E7F]/g"],
```

- Quokka.js
  - New JavaScript File
- ESLint https://eslint.org/

```sh
npm init @eslint/config -- --config semistandard
npm install --save-dev eslint  # For Manual Set Up

npx eslint myfile.js
```

# CSS Framework

- https://getbootstrap.com/docs/5.3/getting-started/vite/
- https://tailwindcss.com/docs/guides/vite
- https://mui.com/material-ui/getting-started/installation/
