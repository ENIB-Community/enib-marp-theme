# ENIB Marp Theme

Marp theme designed in accordance with the ENIB colors.

> ENIB: https://www.enib.fr/fr/

> MARP: https://marp.app/

## Installation

There is two way to use this theme:

- by using the CLI and importing the theme manually.
- by using VS Code and the marp extension.

### VS Code installation

1. open VS Code settings.json

    - `Ctrl+Shift+P`
    - write `user settings`
    - click on `Open User Settings (JSON)`

1. add these lines to your current VS Code config :

    ```json
    {
        "markdown.marp.themes": [
            "https://raw.githubusercontent.com/ENIB-Community/enib-marp-theme/main/themes/enib-theme-dark.css",
            "https://raw.githubusercontent.com/ENIB-Community/enib-marp-theme/main/themes/enib-theme-light.css"
        ]
    }
    ```

Now you can access to ENIB Marp themes from anywhere on your system.

### Install the theme locally

Get the theme(s), and put them in the same folder as your presentation markdown file.

```shell
# light theme
wget https://raw.githubusercontent.com/ENIB-Community/enib-marp-theme/main/themes/enib-theme-light.css 
# dark theme
wget https://raw.githubusercontent.com/ENIB-Community/enib-marp-theme/main/themes/enib-theme-dark.css 
```

## Using the theme

In your markdown file:

```md
---
marp: true
theme: enib-theme-light
---

<!-- content -->
```

```md
---
marp: true
theme: enib-theme-dark
---

<!-- content -->
```
