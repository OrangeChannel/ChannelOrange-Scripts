# How to use these patches:

1. First, make sure your copy has the right checksum. Find the CRC of your local file, and make sure it matches the CRC in the filename.
  
   - You can do this using [RapidCRC](http://rapidcrc.sourceforge.net/download.html) on Windows.
2. Download the correct patch for your version. The CRC in your local filename should match the first CRC of the patch zip.
3. Unpack the archive into the same folder as your file, or into a new folder specifically for patching.
   
   - If you create a new folder, make sure to move your release file into this new folder.
4. Run the Apply Patch - [your OS] file.
5. Verify your new file has the right checksum.
6. Delete old files and patch files.

## Notes

Included in each .zip is a readme file with a step-by-step explanation of how to patch.

There is also sometimes a changelog file, if you're interested in what has been changed/updated.

## How does this work?

It uses [xdelta3](http://xdelta.org/).
