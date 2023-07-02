Generate on mac using CMD-shift-5.
MAKE SURE that you're doing the recording against a white background, and leaving space for the drop shadow (about 1 to 1.25cm on all sides)

1900x1300

That should output a .mov file.

you need to generate a x.webm, x.gif

COMMANDS:
ffmpeg -i recording.mov -c:v libvpx-vp9 -b:v 1000k -an  -f webm recording.webm
ffmpeg -i recording.mov -vf "[0:v] fps=10,scale=800:-1,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse=dither=bayer:bayer_scale=5" recording.gif
