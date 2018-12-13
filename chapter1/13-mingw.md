MinGW为Qt-5.12.0附带的安装的，安装完成后，添加环境变量。

1. 运行终端；
2. bootstrap gcc

3. b2 -j2 stage --build-type=complete --build-dir=mingw toolset=gcc link=shared threading=multi variant=release

4. b2 install --prefix="E:\ProgramData\MinGW\boost-1.68"



