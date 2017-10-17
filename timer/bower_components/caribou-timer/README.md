[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/PolymerElements/caribou-timer)

## &lt;caribou-timer&gt;

`<caribou-timer>` is a Polymer 2 element used to display a timer (Android style)

This element allow you to set a default time. This time can be edited with the plus and minus button.
Or if the attribute 'input-time' is added, it can be edited with the keyboard and the arrow key.

A maximum and minimum limit can be set
Moreover you can set the 'remaining-time' property. If set this property will automatically start the timer,
a the specific point according to the whole-time value
Example:
    '<caribou-timer input-time whole-time="60" max-time-limit="3600" min-time-limit="30"></caribou-timer>
### Styling The following custom properties and mixins are available for styling: 
Custom property | Description | Default
----------------|-------------|----------
 `--editable-text-color` | Time color on the editable field (inputTime=true) | `#64B5F6` 
 `--editable-text-color-disabled` | Time color on the editable field disabled (inputTime=true) | `#64B5F6`
 `--non-editable-text-color`| Time color on the non editable field (inputTime=false)| `#64B5F6`
 `--time-button-color`| Plus and minus button color | `#64B5F6`
 `--time-button-color-disabled`| Disabled plus and disabled minus button color | `#64B5F6`
 `--time-button-color-hover`| Plus and minus button color hover | `#64B5F6`
 `--circle-line-passed-color`| Color of the passed circle line | `#64B5F6`
 `--circle-line-remaining-color`| Color of the remaining circle line | `#64B5F6`
 `--circle-line-endpoint-fill-color`| Fill color or the little circle at the edge of the progression line | `#64B5F6`
 `--circle-line-endpoint-stroke-color` | Stroke color or the little circle at the edge of the progression line |`#64B5F6`
 `--button-start-color` | Button start color | `#64B5F6`
 `--button-pause-color`| Button pause color | `#64B5F6`
 `--button-start-color-hover`| Button start color on hover | `#64B5F6`
 `--button-pause-color-hover`| Button pause color on hover | `#64B5F6`


## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="caribou-timer.html">
    <style>
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<caribou-timer input-time whole-time="60" max-time-limit="3600" min-time-limit="30"></caribou-timer>
```


## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## Running tests from the command line
When in the caribou-timer directory, run polymer test

## License
Apache License 2.0