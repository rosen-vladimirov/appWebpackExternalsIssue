# Demo application demonstrating issue with livesync of external files

## Steps to reproduce
1. Clone the repo
2. Run `tns run <platform>`
3. Apply a change in `app/demo.js` - the change must be shown on device, however CLI does not upload anything.

> NOTE: Te change should be visible in case demo.js is defined as external or even when the WebpackIgnore plugin is used. To test the later scenario, use the `webpack.config_ignore.js` file instead of the current `webpack.config.js`.