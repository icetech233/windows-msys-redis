install msys64 exe

need copy dll  C:\msys64\usr\bin\msys-2.0.dll
···
pacman -Syu
pacman -S --needed base-devel  mingw-w64-x86_64-toolchain
pacman -S libreadline-devel
···
build code

2
unzip  redis-6.2.5\src

redis-server.exe
redis-benchmark.exe
redis-cli.exe




中国github镜像网站

https://hub.fastgit.org/icetech233/msys-redis/raw/master/redis-6.2.5.zip

https://hub.fastgit.org/icetech233/msys-redis/raw/master/dll/msys-2.0.dll




update log  2023-04-14

https://www.msys2.org/

$ pacman -S mingw-w64-ucrt-x86_64-gcc
resolving dependencies...
looking for conflicting packages...

Packages (15) mingw-w64-ucrt-x86_64-binutils-2.39-2
            mingw-w64-ucrt-x86_64-crt-git-10.0.0.r68.g6eb571448-1
            mingw-w64-ucrt-x86_64-gcc-libs-12.2.0-1  mingw-w64-ucrt-x86_64-gmp-6.2.1-3
            mingw-w64-ucrt-x86_64-headers-git-10.0.0.r68.g6eb571448-1
            mingw-w64-ucrt-x86_64-isl-0.25-1  mingw-w64-ucrt-x86_64-libiconv-1.17-1
            mingw-w64-ucrt-x86_64-libwinpthread-git-10.0.0.r68.g6eb571448-1
            mingw-w64-ucrt-x86_64-mpc-1.2.1-1  mingw-w64-ucrt-x86_64-mpfr-4.1.0.p13-1
            mingw-w64-ucrt-x86_64-windows-default-manifest-6.4-4
            mingw-w64-ucrt-x86_64-winpthreads-git-10.0.0.r68.g6eb571448-1
            mingw-w64-ucrt-x86_64-zlib-1.2.12-1  mingw-w64-ucrt-x86_64-zstd-1.5.2-2
            mingw-w64-ucrt-x86_64-gcc-12.2.0-1

Total Installed Size:  397.59 MiB

:: Proceed with installation? [Y/n]
[... downloading and installation continues ...]
Now you can call gcc to build software for Windows.


$ gcc --version
gcc.exe (Rev1, Built by MSYS2 project) 12.2.0


