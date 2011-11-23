# OpenD3
OpenD3 is a free and opensource implementation of Doom 3. This project is based on the Doom 3 GPL source code, release by id Software on 2011. The main objective is a free and open source game based on the released code, similar to previous efforts like FreeDoom or OpenArena.

## Compiling on Windows
Visual Studio project available in neo\doom.sln. You'll need the June 2010 DirectX SDK.

## Compiling on Linux
The build system uses SCons, so you just need to run scons from the neo directory. In a Debian/Ubuntu system:

```bash
apt-get install scons
```

You will also need the following libs:

```bash
apt-get install libglu-dev libxxf86vm-dev libopenal-dev libasound2-dev
```

## Compiling on Mac
XCode project available in neo/sys/osx.

## License
See COPYING.txt for the GNU GENERAL PUBLIC LICENSE

ADDITIONAL TERMS:  The Doom 3 GPL Source Code is also subject to certain additional terms. You should have received a copy of these additional terms immediately following the terms and conditions of the GNU GPL which accompanied the Doom 3 Source Code.  If not, please request a copy in writing from id Software at id Software LLC, c/o ZeniMax Media Inc., Suite 120, Rockville, Maryland 20850 USA.

## Readme
See README.txt for the original Doom 3 source release readme.
