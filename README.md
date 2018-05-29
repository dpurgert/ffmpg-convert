# ffmpg-convert
Quick and dirty conversion to mp3.

`convert` takes an arbitrary input format (e.g. ogg) from a selected
input directory; and saves it to the selected output directory in mp3
format.

Input files will not be touched -- removed, renamed, deleted, etc.  The
script merely creates a transcoded copy in the desired output directory.

## Usage
`convert </input/path> </output/path> <ext>`

* </input/path> is the full or relative path where the input file(s) are
* </output/path> is the full or relative path you wish to save file(s)
* <ext> is the three-character file extension (e.g. "mp4")

## TODO

List of things I should probably do at some point:
* Select arbitrary output format / codec

## Prerequisites / Notes
This is written against ffmpeg 3.3.4 (specifically on MX Linux), and has
only been tested on said system. 

There may be other prereqs / codecs that I'm not considering as they
slipped in as part of a metapackage (sorry!)
