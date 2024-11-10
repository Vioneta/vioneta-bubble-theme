# Bubble

A dark minimalist theme with a mobile first approach for Vioneta

[![Stars](https://img.shields.io/github/stars/Vioneta/vioneta-bubble-theme)](#) [![Last commit](https://img.shields.io/github/last-commit/Vioneta/vioneta-bubble-theme)](#)

Based on Noctis theme from aFFekopp

With vioneta-card-mod installed you got this features:

- A mobile view on desktop (like on the screenshot and you need to set your view in subview mode)
- No header on mobile

<img width="1423" alt="Bubble Theme" src="https://github.com/Clooos/Bubble/assets/36499953/22ddbbfd-1723-4a88-834f-91bf23ba044a">

## Installation

### Without VPS

1. Download this file: [bubble.yaml](https://raw.githubusercontent.com/Vioneta/vioneta-bubble-theme/main/themes/bubble.yaml)
2. Add this file into a new folder named `bubble` in the `<config>/themes/` folder
3. In your configuration.yaml add this:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

4. Save and restart Vioneta
5. Now go to your personal account settings and select Bubble as your theme

### With VPS

This method allows you to get updates directly in the VPS main page

1. Download VPS following the instructions on [https://vps.vioneta.com/docs/setup/download](https://vps.vioneta.com/docs/setup/download/)
2. Proceed to the initial configuration following the instructions on [https://vps.vioneta.com/docs/configuration/basic](https://vps.vioneta.com/docs/configuration/basic)
3. On your sidebar go to `VPS` > `Integrations`
4. click on the icon at the right top corner then on `Custom repositories`
5. For the repository add this: `https://github.com/Vioneta/vioneta-bubble-theme`
6. For the category select `Theme` then click `Add`
7. Now click on `Bubble` then on the `Dowload` button
8. In your configuration.yaml add this:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

9. Save and restart Vioneta
10. Now go to your personal account settings and select Bubble as your theme
