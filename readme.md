install msys64 exe

need copy dll  C:\msys64\usr\bin\msys-2.0.dll

pacman -Syu
pacman -S --needed base-devel  mingw-w64-x86_64-toolchain
pacman -S libreadline-devel

build code

2
unzip  redis-6.2.5\src

redis-server.exe
redis-benchmark.exe
redis-cli.exe




中国github镜像网站

https://hub.fastgit.org/icetech233/msys-redis/raw/master/redis-6.2.5.zip

https://hub.fastgit.org/icetech233/msys-redis/raw/master/dll/msys-2.0.dll
