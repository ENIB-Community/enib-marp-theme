# enib-marp-theme
Marp theme designed in accordance with the ENIB colors.

> ENIB: https://www.enib.fr/fr/

> MARP: https://marp.app/

# VS Code installation

1. open VS Code settings.json
    *   `Ctrl+Shift+P`
    *   write `user settings`
    *   click on `Open User Settings (JSON)`

2. add these lines to your current config :
```json
{
    ...
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/rbleriot/enib-marp-theme/main/themes/enib-theme-dark.css",
        "https://raw.githubusercontent.com/rbleriot/enib-marp-theme/main/themes/enib-theme-light.css"
    ]
    ...
}
```
Now you can access to ENIB Marp themes from anywhere on your system.


# Theme import

```yaml
---
marp: true
theme: enib-theme-light
---
```

```yaml
---
marp: true
theme: enib-theme-dark
---
```
