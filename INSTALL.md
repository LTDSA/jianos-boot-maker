# 安装

If you want binary install, please see [README](README.md).

## Linux平台

### 开发环境

- 基于debian发布

### 安装编译依赖

```bash
sudo apt-get install debhelper python qt5-default qt5-qmake qttools5-dev-tools lib-dev lib-dev libdtkwidget-dev
```

### 编译简OS启动盘制作器

```
mkdir build
cd build
qmake -r ..
make
```

## Windows平台

### 开发环境

- Windows 10 64位
- Microsoft Visual C++ 2017
- Windows SDK
- Qt5.8
- Dtk

### Build Qt static

```
configure -prefix "C:\Qt\QtStatic\5.8\vs2017" -release -platform win32-msvc2010 \
-no-qml-debug -confirm-license -opensource -static -qt-pcre -no-icu -no-sql-sqlite \
-no-nis -no-cups -no-iconv -no-dbus -nomake examples -no-sql-odbc -no-compile-examples \
-skip qtwebkit -skip qtwebkit-examples -skip qtactiveqt -no-openssl -qt-zlib \
-qt-libpng -qt-freetype -qt-libjpeg -opengl es2 -angle
```

### 编译Dtk

TODO

### 编译简OS启动盘制作器

```
mkdir build
cd build
qmake -r ..
nmake
```


## Mac OSX平台

### 开发环境

- Mac OS 10.12
- Qt5.8

### 设置Qt路径

```
export QtInstallPath=/User/yourhome/Qt5.8/5.8/clang_64
export PATH=$QtInstallPath/bin:$PATH
```
### 编译Dtk

TODO

### 编译简OS启动盘制作器

```
mkdir build
cd build
qmake -r ..
make
macdeployqt src/app/deepin-boot-maker.app
```
