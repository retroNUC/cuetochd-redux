# CueToChd Redux

Fork of [undeadindustries/cuetochd](https://github.com/undeadindustries/cuetochd) with further improvements to the PowerShell scripts. 

## Features/Fixes
Implemented so far (on top of cuetochd):
- Better handling of files and directories with problematic characters
- Support for more file formats that chdman also supports, such as .iso and .gdi
- Temporary directory for extraction now cleans itself up
- Files/folders processed in alphabetical order (was previously random)
- Updates to 7zip/chdman executables
- Probably more changes?

## Wishlist
- Better error handling / report of failed files
- Powershell-style progress bars
- Upfront scan and analysis of files/folders, along with remaning time estimation
- Packaging to standard executable, simple drag-and-drop support
- Auto-update functionality for dependencies (MAME chdman, 7-Zip) 

## License
- Distributed under GNU Lesser General Public License v3.0
- Components ([MAME chdman](https://github.com/mamedev/mame/), [7-Zip](https://www.7-zip.org/)) also distributed under GNU LGPL
