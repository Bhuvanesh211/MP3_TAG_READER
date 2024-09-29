# MP3_TAG_READER
MP3 tag reader is a software which will read and display MP3 (ID3) tag information from MP3 files. The software will be desktop based and not web based. This solution will read the given MP3 file, extract various tag information and display them via command line. This project can be extended to implement a tag editor, where-in users can modify mp3 tag information.


# Pre-requisite:
a.Function pointers
b.String operations
c.File I/O handling

# Requirement Details
Here is the list of requirements that your MP3 tag reader should be in a position to handle. 

Mandatory Features:
1.This application, should be able to handle all ID3 versions (Except v2.4) tags.
2.Display which version of ID3 tag is used.
3.Display all the metadata information from ID3 tag.
4.User should be able to change tags according to options given.
5.Should display a help screen on request (-h option).
6.If any image embedded in file, display details about image (Type, path and size).
7.If ID3 tag not found display proper error messages.

# Additional Features:
1.Add an option to extract the album art (image) from file.
2.Add an option to delete all tag data from the file.
3.In corporate ID3v2.4 version.
4.It should be possible to delete a selected tag by options.

# References
Wikipedia – ID3 Article(https://en.wikipedia.org/wiki/ID3)
ID3 Specification Website(https://id3.org)
Download project document in PDF format(https://www.emertxe.com/embedded-programming/embedded-c-projects/mp3-tag-reader.pdf)
