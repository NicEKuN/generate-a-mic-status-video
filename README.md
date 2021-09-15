# generate-a-mic-status-video
generate a video from detection audio.
base on jumpcutter by kivancyuksel
all of this code used python.

## Installation
first you have to install all package requirements
```
pip install -r requirements.txt
```

## All command
**Required <br />
`--input`, `-i`: Path to the video or audio that you want to use for generate a video. <br />
`--output`, `-o`: Path to where you want to save the output video. <br />
`--default_img`, `-d_`: Path to the inactive image file. <br />
`--active_img`, `-a_`: Path to the active image file. <br />
*Advance <br />
`--silence-part-speed`, `-x`: If this parameter is given, instead of cutting the silent parts out, the script will speed them up "x" times.<br />


## Examples of running the program
*The simplest way you can run the program
```
py __main__.py -i input_path -o output_path -d_ default_img_path -a_ active_img_path
```
