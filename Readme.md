### BoardGenerator
生成一张用于显示在IPAD2018上的标定板图像

默认分辨率为2048x1536，9行12列的标定板图片

程序中权重的含义为整张图片去除圆点所占区域（也就是剩下的空白区域），左右（或者上下）区域的比值

生成的图片以圆点间隔命名

### DIC
将包含DIC计算参数的json文件拖到opencorr.exe上，可以开始计算。关于json字典中各类别值的信息如下：

#define DIC_TYPE_2D "plane"
#define DIC_TYPE_3D "stereo"
#define DIC_TYPE_INCREMENTAL_2D "incremental_2D"
#define DIC_TYPE_INCREMENTAL_3D "incremental_3D"

#define COARSE_METHOD_SIFT     "sift"
#define COARSE_METHOD_FFTCC    "fftcc"
#define COARSE_METHOD_EPIPOLAR "epipolar"
#define REFINE_METHOD_ICGN     "icgn"
#define REFINE_METHOD_ICGN2ND  "icgn2"

#define INTERPOLATOR_BICUBIC         "bicubic"
#define INTERPOLATOR_BSPLINE_BICUBIC "bspline_bicubic"
#define INTERPOLATOR_BILINEAR        "bilinear"

#define GRADIENT_ORDER_2 "O2"
#define GRADIENT_ORDER_4 "O4"
#define GRADIENT_ORDER_8 "O8"

#define POI_MODE_AUTO    "auto"
#define POI_MODE_SHAPE   "shape"
#define POI_MODE_MANUAL  "manual"
#define POI_MODE_SUBFILE "subfile"

#define POI_MODE_SHAPE_RECT  "rect"#define DIC_TYPE_2D "plane"
#define DIC_TYPE_3D "stereo"
#define DIC_TYPE_INCREMENTAL_2D "incremental_2D"
#define DIC_TYPE_INCREMENTAL_3D "incremental_3D"

#define COARSE_METHOD_SIFT     "sift"
#define COARSE_METHOD_FFTCC    "fftcc"
#define COARSE_METHOD_EPIPOLAR "epipolar"
#define REFINE_METHOD_ICGN     "icgn"
#define REFINE_METHOD_ICGN2ND  "icgn2"

#define INTERPOLATOR_BICUBIC         "bicubic"
#define INTERPOLATOR_BSPLINE_BICUBIC "bspline_bicubic"
#define INTERPOLATOR_BILINEAR        "bilinear"

#define GRADIENT_ORDER_2 "O2"
#define GRADIENT_ORDER_4 "O4"
#define GRADIENT_ORDER_8 "O8"

#define POI_MODE_AUTO    "auto"
#define POI_MODE_SHAPE   "shape"
#define POI_MODE_MANUAL  "manual"
#define POI_MODE_SUBFILE "subfile"

#define POI_MODE_SHAPE_RECT  "rect"
