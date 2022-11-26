# 🏠 Smart Home Configuration
This repository holds the [Home Assistant](https://www.home-assistant.io) configuration for my Smart House.

A huge thank to the growing [Home Assistant Community](https://community.home-assistant.io) for the inspiration to continually develop and grow my smart home!
<p>
<img src="https://img.shields.io/github/stars/unofficialmatt/home-assistant-v2.svg?style=plasticr"/>
<img src="https://img.shields.io/github/commit-activity/y/unofficialmatt/home-assistant-v2.svg"/>
<img src="https://img.shields.io/github/last-commit/unofficialmatt/home-assistant-v2.svg?style=plasticr"/>
<img src="https://img.shields.io/github/issues/unofficialmatt/home-assistant-v2.svg"/>
<img src="https://img.shields.io/badge/license-Unlicense-blue.svg"/>
</p>

## Global Information

### Automations

[Turn devices off when Home Status changes to 'Away'](https://github.com/unofficialmatt/home-assistant-v2/blob/master/packages/presence/home_status.yaml) - includes lights

## Downstairs rooms

<table style="width:100% !important">
<thead style="text-align: left;">
<tr>
<th colspan="2" style="text-align:left">

### <a name="lounge"></a> Room: Lounge

</td>
</tr>
</thead>
<tbody>
<tr>
<td width="40%">

#### Devices

</td>
<td width="60%">

#### Automations

</td>
</tr>
<tr valign="top">
<td width="40%">
<details>
<summary>Lights</summary>

[Philips Hue White and Color B22](https://www.philips-hue.com/en-gb/p/hue-white-and-colour-ambiance-1-pack-e27/8719514328204) in ceiling mounted pendant lights x 2

[Philips Hue White and Color E14](https://www.philips-hue.com/en-gb/p/hue-white-and-colour-ambiance-1-pack-e27/8719514328204) in floor lamp

</details>
<details>
<summary>Switches</summary>

[Philips Hue Dimmer Switch](https://www.philips-hue.com/en-gb/p/hue-dimmer-switch--latest-model-/8719514274617#overview) installed over wallswitch with 3D printed mountplate

</details>
<details>
<summary>Media</summary>

[Google Home Smart Speaker White](https://mobiledirectonline.co.uk/product/google-home-smart-speaker/?attribute_pa_colours=white)

</details>
</td>
<td width="60%">

Dimmer Switch configured via Hue App

</td>
</tr>
</tbody>
</table>

<table style="width:100% !important">
<thead style="text-align: left;">
<tr>
<th colspan="2" style="text-align:left">

### <a name="lounge"></a> Room: Downstairs Toilet

</td>
</tr>
</thead>
<tbody>
<tr>
<td width="40%">

#### Devices

</td>
<td width="60%">

#### Automations

</td>
</tr>
<tr valign="top">
<td width="40%">
<details>
<summary>Lights</summary>

[Philips Hue Filament Standard B22](https://www.philips-hue.com/en-gb/p/hue-white-filament-1-pack-a60-b22-filament-standard/8718699688844) in ceiling mounted pendant light

</details>
<details>
<summary>Sensors</summary>

[Mi Window and Door Sensor](https://www.mi.com/global/product/mi-window-and-door-sensor/) installed on door frame

</details>
</td>
<td width="60%">

[Turn light on when the door is opened](https://github.com/unofficialmatt/home-assistant-v2/blob/master/packages/lights/downstairs_toilet.yaml)

[Turn light off when the room has been occupied, and the door is opened](https://github.com/unofficialmatt/home-assistant-v2/blob/master/packages/lights/downstairs_toilet.yaml)

</li>
</ul>
</td>
</tr>
</tbody>
</table>