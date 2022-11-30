# Theme dracula-x-one-dark-pro

## About

This VS Code theme is a mix between [Dracula Theme](https://draculatheme.com/visual-studio-code) and [One Dark Pro Theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme). I use all the tokenColors of One Dark Pro but inside the UI of Dracula (Background Color / Menu Color)

## Modification

You can easily change some settings in `themes/dracula-x-one-dark-pro.json`, Run the debugger for a preview and use the VS Code commande `>Developer: Inspect Editor Tokens and Scopes ` to see witch parameter affect witch component, see also [Theme Color](https://code.visualstudio.com/api/references/theme-color).

[Here](https://www.youtube.com/watch?v=pGzssFNtWXw) is a good video explaining how to create a theme

## Instalation
First of all you will need `vsce`:

````
npm install -g vsce
````
Then : 
````
git clone https://github.com/launay12u/dracula-x-one-dark-pro
vsce package
code --install-extension dracula-x-one-dark-pro-1.0.0.vsix
````

Now the theme will be listed in VS Code and you can

**Enjoy!**
