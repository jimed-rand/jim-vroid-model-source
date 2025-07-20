# Jim's VRoid model sources
Jim's VRoid models are sourced in version 4.3.1-pure-man. The public can use these sources free of charge and under the GNU General Public License v3.0.

# Ethical use
Follow the established ethics for using these models before use. Use these models as templates or bases for your creations, attributing them if you use them to create VTuber models based on these sources. You can use any license on your model, regardless of the source, when exporting it into VRM. Here's the ethical guide you need to follow.

- Do not use these models for impersonating me [(James Ed Randson)](https://github.com/jimed-rand) in any way, whether that be to scam people or commit any other criminal actions.
- [Subject to the terms of the license we use.](https://www.gnu.org/licenses/gpl-3.0.en.html)

# How to fetch the sources
To make the sources work, you need to download the branch archive I created and rename it to `jimedrand-4.3.1-pure-man-sources.vroid` using the commands below. But before that, you need to install `unzip` and `wget` first on your Unix-like systems. 
```bash
wget -c -O temp.zip https://github.com/jimed-rand/jim-vroid-model-source/archive/refs/heads/4.3.1-pure-man.zip && bsdtar -xf temp.zip --strip-components=1 && zip -r jimedrand-4.3.1-pure-man-sources.vroid thumbnails/ v1model/ LICENSE README.md meta.json && rm temp.zip
```
