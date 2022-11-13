# List of iOS and iPadOS devices edit guide

This is a template guide for editing iOS and iPadOS device tables in [Wikipedia](https://en.wikipedia.org/wiki/List_of_iOS_and_iPadOS_devices)

## Models
Models can be divided into these parts:
* iPhone
* iPad
* iPod touch
* Apple TV (TBD)
* Apple Watch

### iPhone
iPhone models have three tables:
* Supported - All iPhone models which are able to receive latest iOS version will be categorized at here, regardless the iPhone model is in current production or discontinued.
* Unsupported (64-bit) - All iPhone models with 64-bit architecture CPU (A7 chip and later) which no longer receive latest iOS updates (excluding security updates) will be categorized at here.
* Unsupported (32-bit) - All iPhone models with 32-bit architecture CPU (A6 chip and earlier) which no longer receive latest iOS updates (excluding security updates) will be categorized at here. **This table will no longer be updated.**

The first column of each table will be the latest iPhone model. For example:
* Supported - iPhone 14 Pro Max, iPhone 14 Pro ... iPhone 8 Plus, iPhone 8
* Unsupported (64-bit) - iPhone 7 Plus, iPhone 7 ... iPhone 5S
* Unsupported (32-bit) - iPhone 5C ... iPhone (1st generation)

### Table Criteria
<table>
<tr>
<th colspan="2">Table Header</th>
<th>Description</th>
<th>Example</th>
</tr>
<tr>
<th colspan="2">Model</th>
<td>The name of the iPhone model</td>
<td style="text-align: center;">
    iPhone 14 Pro Max<br/>
    iPhone 14 Plus<br/>
    iPhone SE (3rd generation)
</td>
</tr>
<tr>
<th colspan="2">Initial Release operating system</th>
<td>The first public release of iOS available to the iPhone model</td>
<td style="text-align: center;">
    iOS 16.0<br/>
    iOS 15.4<br/>
    iOS 11.0.1
</td>
</tr>
<tr>
<th colspan="2">Latest Release operating system</th>
<td>The latest release of iOS available to the iPhone model</td>
<td style="text-align: center;">
    iOS 16.1.1<br/>
    iOS 15.7.1
</td>
</tr>
<tr>
<th rowspan="23">Display</th>
<th>Screen Size</th>
<td>
    The display size of the iPhone model.<br/>
    Starts with the diagonal, then the height by width. Separate the diagonal size and height by width size with different lines.<br/>
    Use inches as the main unit and millimeter as sub unit with brackets.
</td>
<td style="text-align: center;">
    6.69 in (170 mm) (diagonal)<br/>
    6.07 by 2.8 in (154 by 71 mm)<br/><br/>
    Code Segment:

```
{{convert|6.69|in|mm|abbr=on}} (diagonal)<br>
{{convert|6.07|by|2.8|in|mm|abbr=on}}
```
</td>
</tr>
<tr>
<th>Backlight</th>
<td>
    Light source of a display. Only applicable for LCD displays. Use N/A for iPhone with Super Retina HD/Super Retina XDR (OLED) display.
</td>
<td style="text-align: center;">
    LED-backlit or N/A<br/><br/>
    Code Segment:

```
[[LED-backlit LCD display|LED-backlit]] 
{{N/A}}
```
</td>
</tr>
<tr>
<th>
Multi-touch
</th>
<td>
    Capability for a display to recognize more than one finger contacted. By default, this is stated as "Yes" to all iPhone models.
</td>
<td style="text-align: center;">
<span style="background-color:#9EFF9E">Yes</span> or <span style="background-color:#FFC7C7">No</span>
</td>
</tr>
<tr>
<th>
    Technology
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Resolution
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Pixel Density (ppi)
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Aspect Ratio
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Typical Max brightness ( cd/m<sup>2</sup>)
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    HDR Max brightness ( cd/m<sup>2</sup>)
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Outdoor Max brightness ( cd/m<sup>2</sup>)
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Contrast ratio (typical)
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Fingerprint-resistant oleophobic coating
</th>
<td>
</td>
<td rowspan="9" style="text-align: center;">
<span style="background-color:#9EFF9E">Yes</span> or <span style="background-color:#FFC7C7">No</span>
</td>
</tr>
<tr>
<th>
    Full sRGB Display
</th>
<td>
    Ability to display 100% of sRGB color gamut coverage. Available on iPhone 5 and later. 
</td>
</tr>
<tr>
<th>
    Wide Color Display (Display P3)
</th>
<td>
    Ability to display 100% of Display P3 (P3-D65) color gamut coverage, which has 25% larger color space compare to sRGB. Available on iPhone 7 and later
</td>
</tr>
<tr>
<th>
    True Tone Display
</th>
<td>
    Ability to adjust the color and intensity of the display to match the ambient light by using ambient light sensors. Available on iPhone 8 and later.
</td>
</tr>
<tr>
<th>
    Night Shift
</th>
<td>
    Ability to adjust the color of the display to the warmer end of the specture to make the display easier on the eyes. Available on iPhone 5S and later.
</td>
</tr>
<tr>
<th>
    ProMotion Display
</th>
<td>
    An adaptive refresh rate technology that supports from 10 Hz to 120 Hz and automatically adjusts the refresh rate based on the display content. Available on iPhone 13 Pro and iPhone 14 Pro.
</td>
</tr>
<tr>
<th>
    Always-On Display
</th>
<td>
    Ability to dims the lock screen while showing notifications by operating the refresh rate to 1 Hz. Available on iPhone 14 Pro.
</td>
</tr>
<tr>
<th>
    HDR Display
</th>
<td>
</td>
</tr>
<tr>
<th>
    HDR 10 Content
</th>
<td>
</td>
</tr>
<tr>
<th>
    Dolby Vision
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<th>
    Dynamic Island
</th>
<td>
</td>
<td style="text-align: center;">
<span style="background-color:#9EFF9E">Yes</span> or <span style="background-color:#FFC7C7">No</span>
</td>
</tr>
<tr>
<th>
    Taptic
</th>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td rowspan="2">rowspan2</td>
<td>rowspan1</td>
</tr>
<tr>
<td>rowspan1</td>
</tr>
</table>
