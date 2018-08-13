# Stars BG

#### Download .zip of project

1. Click the green "Clone or download" button in the upper right
2. Choose "Download zip"
3. Move the package to your preferred working folder (it's ok to leave it where it is) and unzip


#### Display in browser

1. Go in to the unzipped folder and right click on `index.html`
2. Choose "Open with..." and select your preferred web browser


#### Change dust img

Two ways:

- Place new image in the project's `img` folder and use a text editor (TextEdit, Sublime Text, etc.) to change line 13 of `index.html` to the correct file name.
- Change the url in line 13 of `index.html` to the proper location of the img file you are working on. This way, you won't have to copy the updated file every time you make any changes.

**After any updates (code or new/edit image), refresh the browser to see your changes take effect.**

#### Opacity

- There is a placeholder opacity style on the `<img>` tag, via the rule on line 50 in `styles.css`. It is defaulted to 1 (100%), which effectively disables the effect. 
- To edit the opacity percentage of the dust image, simply change this value to the desired opacity level (on a scale from 0 to 1), e.g. `0.5` (50%), `0.25` (25%), etc. 
- To remove the effect, set this value back to `1`.
- To see just the stars with no dust overlay, set this value to `0`