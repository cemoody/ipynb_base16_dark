IPython Dark Theme (based on Base16 railscasts dark). Defaults to vim bindings.

[Screenshot](http://i.imgur.com/7sDIkc7.png)
![Screenshot](http://i.imgur.com/7sDIkc7.png)

To use this repo:

1. Download the [Computer Modern Fonts](http://checkmyworking.com/cm-web-fonts/). "custom.css" expects the Monaco and "CMU Serif" fonts to be installed.
1. Create the ipython profile: `ipython profile create dark`
2. Move to the custom files dir: `cd ~/.ipython/profile_dark/static`
2. Move the existing folder away: `mv custom custom-old`
2. Clone the repo `git clone https://github.com/cemoody/ipynb_base16_dark.git custom`
3. Launch IPython `ipython notebook --profile=dark`
