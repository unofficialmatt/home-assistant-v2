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


## Downstairs rooms

<table border="0" width="100%">
  <thead>
    <tr>
      <th colspan="2" style="text-align:left">
        ### <a name="lounge"></a> Room: Lounge
      </td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="40%">#### Devices</td>
      <td width="60%">#### Automations</td>
    </tr>
    <tr valign="top">
      <td width="40%">
        <details>
          <summary>Lights</summary>
          <ul style="margin-top:0.5em;">
            <li><a href="https://www.philips-hue.com/en-gb/p/hue-white-and-colour-ambiance-1-pack-e27/8719514328204">Philips Hue White and Color B22</a> in ceiling mounted pendant lights x 2</li>
            <li><a href="https://www.philips-hue.com/en-gb/p/hue-white-and-colour-ambiance-1-pack-e27/8719514328204">Philips Hue White and Color E14</a> in floor lamp</li>
          </ul>
        </details>
        <details>
          <summary>Switches</summary>
          <ul style="margin-top:0.5em;">
            <li><a href="https://www.philips-hue.com/en-gb/p/hue-dimmer-switch--latest-model-/8719514274617#overview">Philips Hue Dimmer Switch</a> installed over wallswitch with 3D printed mountplate</li>
          </ul>
        </details>
        <details>
          <summary>Media</summary>
          <ul style="margin-top:0.5em;">
            <li><a href="https://mobiledirectonline.co.uk/product/google-home-smart-speaker/?attribute_pa_colours=white">Google Home Smart Speaker White</a></li>
          </ul>
        </details>
      </td>
      <td width="60%">
        <ul style="margin-top:0.5em;">
          <li>Dimmer Switch configured via Hue App</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<table border="0" width="100%">
  <thead>
    <tr>
      <th colspan="2" style="text-align:left">
        ### <a name="lounge"></a> Room: Downstairs Toilet
      </td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="40%">#### Devices</td>
      <td width="60%">#### Automations</td>
    </tr>
    <tr valign="top">
      <td width="40%">
        <details>
          <summary>Lights</summary>
          <ul style="margin-top:0.5em;">
            <li><a href="https://www.philips-hue.com/en-gb/p/hue-white-filament-1-pack-a60-b22-filament-standard/8718699688844">Philips Hue Filament Standard B22</a> in ceiling mounted pendant light</li>
          </ul>
        </details>
        <details>
          <summary>Sensors</summary>
          <ul style="margin-top:0.5em;">
            <li><a href="https://www.mi.com/global/product/mi-window-and-door-sensor/">Mi Window and Door Sensor</a> installed on door frame</li>
          </ul>
        </details>
      </td>
      <td width="60%">
        <ul style="margin-top:0.5em;">
          <li>
          <a href="https://github.com/unofficialmatt/home-assistant-v2/blob/master/packages/lights/downstairs_toilet.yaml">Turn light on when the door is opened</a>
          </li>
          <li>
          <a href="https://github.com/unofficialmatt/home-assistant-v2/blob/master/packages/lights/downstairs_toilet.yaml">Turn light off when the room has been occupied, and the door is opened</a>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>