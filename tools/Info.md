# **Usage & File Info**:

## **romfs-files.txt**
### Info:
* Used by HeavenTool in the generation of ResourceSizeTable.srsizetable
* Necessary to avoid having to use an entire RomFS dump in the generation of ResourceSizeTable.srsizetable and helps avoid errors in the generation of said file.
### Usage:
* Move to "romfs\System\Resource\extra" for usage in the generation of a new ResourceSizeTable.srsizetable
* HeavenTool will automatically create the "extra" directory next to the ResourceSizeTable.srsizetable upon opening it if not present. However, the resulting romfs-files.txt will be empty so replace with this version if an empty file exists.
