A pragmatic [fork of flagello/Essence](https://github.com/flagello/Essence) mixing my [inline toolbar style](https://github.com/Microsoft/vscode/pull/12628)

![Showcase](showcase/i/E1.png)

---

## Using

### Traffic Lights

Set the user setting `"window.titleBarStyle": "custom"`.

### Colors

You need to use the extension "[Custom CSS and JS Loader](https://github.com/be5invis/vscode-custom-css)" - search and install it.

Then clone this repo.

```
git clone https://github.com/orta/Essence.git
```

Set a user preference for your custom CSS:

```
  "vscode_custom_css.imports": [
      "file:///Users/orta/dev/misc/Essence/essence.css"
  ],
```

Run the command "Enable Custom CSS and JS".

Restart VS Code.

### Done

You will see "Your Code installation appears to be corrupt. Please reinstall." on every new window, press escape to make it go away. You have modded VS Code

I use the color theme "Ayu Light". If you find others that fit well, I'd love to make a list in here, send me a PR.

---

### Want to make improvements?

The front-end is just a website, so you can use the chrome web inspector to make your changes. What I do is use the command "Developer: Toggle Developer Tools" then dig through the DOM to find the element to style.

You can make your changes at runtime to verify them, then add them to the CSS file. Then validate they work by doing "Reload Window".
