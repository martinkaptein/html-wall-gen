# html-wall-gen

Python based HTML wallpaper listing generator.

## Usage

Clone this repository:

`git clone https://github.com/martinkaptein/html-wall-gen.git`

Put all of your desired pictures into the `html-wall-gen/` folder.

Edit metadata inside `index.constr`. Optionally, you can edit the exclusion list inside the `generate.py` script.
For the files contained in this list, the script will not generate Hyperlinks.
This already contains sane defaults (hence, it is not **required** to be edited).

When you are done, just run the Python script.

```
cd html-wall-gen/
python generate.py
```

You are presented with a `index.html` file, which contains everything.
You can now upload the entire folder to your web server

## Notes

The index construct contains a very basic design.
Feel free to turn it into something more beautiful.

Also, it should be kept in mind, that on every run, the generation script creates the links from scratch.
This means, if you would like to remove something, just remove the image files, and re-run the script.

This repository contains already an example wallpaper (`polygon-mountain.png`).
I found this one in a theme on the Chrome Web store, but I do not know the license associated with it.

## Troubleshooting

If something doesn't work, it is probably due to read/write permission issues on your system.

## Contact

If you run into further issues, feel free to [contact me on my website](https://www.martinkaptein.com/contact/).
