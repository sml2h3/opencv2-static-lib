## 1、target_include_directories
```
path\to\opencv2-static-lib\include
path\to\opencv2-static-lib\include\opencv2
```

## 2、target_link_directories
```
path\to\opencv2-static-lib\x64\vc17\staticlib
```

## 3、target_link_libraries
```
ade.lib
IlmImf.lib
ippicvmt.lib
ippiw.lib
ittnotify.lib
libjpeg-turbo.lib
libopenjp2.lib
libpng.lib
libprotobuf.lib
libtiff.lib
libwebp.lib
opencv_world455.lib
quirc.lib
zlib.lib
```

## 4、include the .h file in your .cpp file
```
#include <opencv2/opencv.hpp>
#include <opencv2/core/utils/logger.hpp>
#include <opencv2/imgcodecs.hpp>
#include <opencv2/imgcodecs/legacy/constants_c.h>
（...根据需要增加）
```
