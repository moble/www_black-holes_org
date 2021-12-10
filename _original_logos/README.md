I created the favicon with Imagemagick's `convert` command:

    convert sxs_logo_notext_1549px.png -define icon:auto-resize=256,64,48,32,16 favicon.ico

The original favicon is included here as favicon1.  It has very low resolution, though the design is
also tweaked to deal with this low resolution.  Still, it is unacceptable for modern hi-res screens.
