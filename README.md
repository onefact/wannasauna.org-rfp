# letter-template
One Fact Foundation letter template

# Typesetting

We use https://typst.app/ with the following Visual Studio code extensions:

* https://marketplace.visualstudio.com/items?itemName=OrangeX4.vscode-typst-sympy-calculator 
* https://marketplace.visualstudio.com/items?itemName=nvarner.typst-lsp

# Typography

The font is "Fairfax HD" which can be downloaded and installed from the releases here: https://github.com/kreativekorp/open-relay/tree/master/FairfaxHD or here: https://www.kreativekorp.com/software/fonts/fairfaxhd/

# Generating image

```bash
magick -density 1200 -quality 100 example-document-on-letterhead.pdf example-document-on-letterhead.webp
```