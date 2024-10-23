# Cac buoc lam viec voi Cmake
- Buoc 1: Tao file .c
- Buoc 2: Tao file CMakelists.txt
    + La dau vao cua he thong Build Cmake de build cac goi phan mem
- Buoc 3: Tao folder Build
    + Cmake tao ra mot loat tep o noi chay no, tot nhat ta nen co mot folder Build
- Buoc 4: Config CMake (Tao file COnfig vaf makefile)
    + CD Build
    + Tuy vao Linux hay Win de chay
      + Linux: cmake ..
      + Win:
        + cmake -G "Unix Makefiles" ..
        + cmake _-DCMAKE_MAKE_PROGRAM="make.exe" -G"Unix Makefiles" ..
- Buoc 5: Build Source Code
    + cmake --build