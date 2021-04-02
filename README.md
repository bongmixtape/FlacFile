## What is it?
FlacFile is a utility for storing arbitrary files in the metadata section of a [FLAC](https://xiph.org/flac/) file.

## What is the format stored in the metadata?
The data is stored in an APPLICATION metadata block with the ID 0x41544348 ("ATCH"):

(1 byte) Description length  
(variable) Description (UTF-8)  
(1 byte) MIME type length  
(variable) MIME type (UTF-8)  
(variable) File contents

## Are there recommended "Description" values?
Yes:
* Front Cover
* Back Cover
* Media
* Artist
* Venue
* Live
* Lyrics
* Credits
* Reflection

## About
This is a copy of the app created by Ian Gulliver. You can still view the original site via [The Wayback Machine](https://web.archive.org/web/http://firestuff.org/flacfile/).

Learn more about FLAC's [APPLICATION metadata blocks](https://xiph.org/flac/format.html#def_APPLICATION).
