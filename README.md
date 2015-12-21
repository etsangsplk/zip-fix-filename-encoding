
# About

Convert filenames inside ZIP archives from autodetected older Russian encodings
(koi8-r, koi8-u, cp866, windows-1251) to UTF-8.

This tool does not touch the file contents, it just renames the files inside
a ZIP archive.

# Build and Install

    test -f configure || autoreconf -iv
    ./configure
    make install

# Usage

    runzip <filename.zip>
