## Pure Data External: PolyBLEP Sawtooth ##

Custom external module for use in Pure Data that outputs a sawtooth wave generated using PolyBLEPs. The waveform retains much of its harmonic content, giving it a rich and deep sound. While the waveform is not completely band-limited, aliasing noise is very minimal if not entirely inaudible in all but the highest frequencies approaching Nyquist.

Xcode 5 and Visual Studio 2010 projects are included for building Mac and Windows libraries. The generated library should be placed in the following folders based on platform:

##### Mac OS X #####
	~/Library/Pd
or

	/Library/Pd
	
##### Windows #####
	%appdata%\Pd
or

	%commonprogramfiles%\Pd

### Dependencies ###

Compilation on Mac OS X seems to work fine without any additional dependencies, but on Windows, *pd.lib* is required. This file is included in the Pd vanilla download [here](http://puredata.info/downloads/pure-data).

---

Pure Data, Copyright (c) 1997-1999 Miller Puckette.
 
This program is free software: you can redistribute it and/or modify it under the terms
of the GNU General Public License as published by the Free Software Foundation, either
version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the  GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.
If not, see <http://www.gnu.org/licenses/>.
