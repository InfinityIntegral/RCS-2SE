# RCS(-2)SE (C++ course slides)

This repository contains slides that can be used in a Computer Science course to teach C++. Since Git does not work with Google Slides (.pptx), each set of slides is split into 2 versions.

In the txt folder you can find all slides in text format available as .txt files in case the pptx does not work or you do not have 7zip.

In the pptx folder you can find slides in the form of Google Slides unzipped into folders so that Git diff works. Assuming that you have 7zip installed properly, you can use

`7z a -tzip [pptx name].pptx .\[folder name]\*`

to zip the folder back into a Google Slides file. You can open it by uploading it onto Google Drive and opening it there using Google Slides.

The command for unzipping Google Slides files is

`7z x [pptx name].pptx -o[folder name]`

The pptx or folder names are always in the format

`[unit group number].[unit number]_[unit name in snake_case]`

An example is

`0.0_I_not_blur`

## Why the name RCS(-2)SE?

This follows the format of Canadian secondary school course codes. RCS means Real Computer Science, -2 corresponds to Secondary 1, S means working towards high standards similar to what we have in Singapore, and E means E-Learning or online asynchronous learning.
