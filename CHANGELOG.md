# Unpublished changes

Features :
- Add color channel iterators (iterator, const_iterator, reverse_iterator, const_reverse_iterator)

Fix :
- Fix the save function in the ImageExporter when saving an image in a non hdr format, with channel value greater than 1.0
- Fix symbols export for installed library
- Fix `Image` move operations
- Fix `Color` move and copy operations
- Fix `Color` reverse iterator, was returning forward iterator instead

# v0.1.1


Features : 
- Clean cmake, and support release and debug installs in the same location (see #2)

Fix :
- CMake won't run due to missing file (see #1)


# v0.1.0

Features : 
- Load image files (JPEG, PNG, BMP, PSD, TGA, GIF, HDR, PIC, PNM)
- Export (JPEG, PNG, BMP, HDR, TGA)
- Basic image edition features
- Cast image color format from one type to another
- Basic operation on colors (+, -, *, /)
- A simple example on how to use the library
- CMake files to install the project or use it as a third party 
