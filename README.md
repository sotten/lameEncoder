# LameEncoder

## ON LINUX ##
1) Install LameLib using:
`$ sudo apt-get install -y lame`
2) Build using:
`$ cmake . && make`
3) Run excutable using:
`$ ./bin/lameEncoder <path>`

## ON WINDOWS ##
1) Install msys, run it, and run following commands:
2) Install gcc:
`$ pacman -S mingw-w64-x86_64-gcc`
3) Install cmake:
`$ pacman -S mingw-w64-x86_64-cmake`
4) Install LameLib using:
`$ pacman -S mingw-w64-x86_64-lame`
5) Generate Makefiles
`cmake -G "Unix Makefiles"`
6) Change to project dir and build using:
`$ cmake . && make`
7) Run excutable using:
`$ ./bin/lameEncoder.exe <path>`
