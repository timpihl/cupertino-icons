# Cupertino Icons

[![Hacs](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/timpihl/cupertino-icons?style=for-the-badge) 
![GitHub Release Date](https://img.shields.io/github/release-date/timpihl/cupertino-icons?style=for-the-badge)

> Apple iOS-like Cupertino style icons for Home Assistant!

## Screenshots

<div style="display: inline-block;">
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/house.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/lightbulb_fill.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/lightbulb.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/alarm.svg" alt="preview" width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/app_badge_fill.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/battery_25.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/bed_double_fill.svg" alt="preview"  width="50"/>
  <br/>
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/camera_fill.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/cloud_moon_rain.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/cloud_sun.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/moon_stars.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/moon_zzz_fill.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/person_crop_circle_badge_checkmark.svg" alt="preview"  width="50"/>
  &#8287;&#8287;&#8287;
<img src="https://github.com/timpihl/cupertino-icons/blob/master/docs/speaker_2_fill.svg" alt="preview"  width="50"/>
</div>

## Install
### HACS (Recommended)
1. Go to the **HACS** tab
2. Frontend
3. Menu > **Custom Repository**
4. Paste this repo's URL
5. Select **Lovelace** in the dropdown
6. Install **cupertino-icons**
7. Reload frontend cache

The icons should be usable in Home Assistant now. If it doesnt show up, try refreshing the page, private browsing or restart Home Assistant

### Manual
1. Clone this repo
2. Copy `dist/HomeAssistant-Cupertino-Icons.js` to `{HOMEASSISTANT_ROOT_DIR}/www/`
3. Home Assistant > **Settings** > **Lovelace Dashboards** > **Resources** > **Add**
   - URL: `/local/HomeAssistant-Cupertino-Icons.js`
   - Resource Type: `JavaScript Module`
  
The icons should be usable in Home Assistant now. If it doesnt show up, try refreshing the page, private browsing or restart Home Assistant

## Usage
Prefix: **ios**  
Eg: **ios:lightbulb-fill** | **ios:cloud-moon-rain** | **ios:bed-double-fill**

## Icon Reference

~P.S.: with only 1216 icons, the iconset is rather small compared to MDI and incredibly limited. The new SF Pro Symbols v2.0+ now has a total of over 2000+ icons. Update coming soon.~

**v2.0.1 Update**  
Home Assistant Cupertino Icons has now been updated to SF Symbols v2.1!

It now supports **2441 Icons**! (Copyrighted icons excluded)

[SF Symbols v2.1 | Apple](https://developer.apple.com/sf-symbols/)  
[SF Symbols Reference | SFSymbols.com](https://sfsymbols.com)

You may download the MacOS App from Apple for a better reference.

**Note:** underscores(\_) and dots(.) must be swapped with hipens(-)  

<hr/>

## To Do
☑️ Upgrade to SF Pro Symbols v2.1
