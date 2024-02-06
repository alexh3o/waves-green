# Waves Theme


This is a green version of waves theme by [Tim Cowell](https://github.com/tgcowell) for Home Assistant 

These themes also include

* Noctis - https://github.com/aFFekopp/noctis

* Caule Theme Pack - https://github.com/orickcorreia/caule-themes-pack-1


## Manual Installation


0. This theme uses 2 custom fonts via Google Fonts, you will need to add these as a resource in order to use the same fonts.
  - Click on configuration within Home Assistant
  - Click on Lovelace Dashboards
  - Click the Resources tab at the top
  - Click the + Add Resource button
  - You will need to add the follow URL and set the resource type to Stylesheet, then click on create. 

**URL To Copy**

```
https://fonts.googleapis.com/css2?family=Oxygen&family=Ubuntu:wght@300&display=swap    
```

1. Download the themes folder from this repo
2. Unzip the contents and extract the themes for into homeassistant/themes/
3. Make sure the following is in your configuration.yaml folder

```
frontend: 
  themes: !include_dir_merge_named themes
```
4. Restart your Home Assistant server
5. Select the theme in your user profile settings


## Backgrounds & Animated Icons
This theme includes 2 backgrounds (light and Dark) along with Animated weather icons, in order to use these please complete the following steps

1. Create the following folder 

/config/www/waves/

2. Download the images located within the themes folder, everything excluding waves.yaml

3. Reload or Restart Home Assistant, your theme should now include the backgrounds and animated images.






