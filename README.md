# MP3 Tag Reader

MP3 Tag Reader is a desktop-based software that reads and displays MP3 (ID3) tag information from MP3 files. This solution reads a given MP3 file, extracts various tag information, and displays them via the command line. The project can be extended to implement a tag editor, allowing users to modify MP3 tag information.

## Features

### Mandatory Features
1. **ID3 Version Handling**
   - Handles all ID3 versions except v2.4 tags.
2. **ID3 Version Display**
   - Displays the version of the ID3 tag used in the MP3 file.
3. **Metadata Display**
   - Displays all metadata information from the ID3 tag.
4. **Tag Modification**
   - Allows the user to change tags based on provided options.
5. **Help Screen**
   - Displays a help screen on request using the `-h` option.
6. **Image Information**
   - If an image is embedded in the file, displays details about the image (type, path, and size).
7. **Error Handling**
   - Displays proper error messages if no ID3 tag is found.

### Additional Features
1. **Album Art Extraction**
   - Option to extract the album art (image) from the file.
2. **Tag Data Deletion**
   - Option to delete all tag data from the file.
3. **ID3v2.4 Version Handling**
   - Incorporates ID3v2.4 version handling.
4. **Selective Tag Deletion**
   - Allows the deletion of selected tags based on provided options.

## Pre-requisites

- Function pointers
- String operations
- File I/O handling

## References

- [Wikipedia – ID3 Article](https://en.wikipedia.org/wiki/ID3)
- [ID3 Specification Website](https://id3.org)
- [Project Document in PDF](https://www.emertxe.com/embedded-programming/embedded-c-projects/mp3-tag-reader.pdf)


