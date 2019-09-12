• tutorial_code/: opencv教程代码

• 3calibration.cpp: 同时标定三台水平放置的相机。

• bagofwords_classification.cpp: 使用图像检测实现简易的图像搜索功能。

• bgfg_gmg.cpp: 演示GMG 背景检测算法的使用方式。

• bgfg_segm.cpp: 演示高斯混合背景检测算法的使用方式。

• brief_match_test.cpp: 使用 BRIEF 特征值来匹配两张图像。

• build3dmodel.cpp: 演示如何使用基础矩阵和特征值来创建三维模型。

• calibration.cpp: 完整的多用途标定程序。

• calibration_artificial.cpp: 在程序中生成一个虚拟的相机，并进行标定。

• camshiftdemo.cpp: 读取实时的摄像头数据，并演示基于均值偏移算法的视频跟踪。

• chamfer.cpp: 使用Chamfer 算法匹配两副边缘图像。

• cloning_demo.cpp: 命令行模式的图像克隆。

• cloning_gui.cpp: 图形界面交互的图像克隆。

• connected_components.cpp: 查找并绘制图像中的连通区域。

• contours2.cpp: 查找并绘制图像中的轮廓。

• convexhull.cpp: 查找并绘制由点的集合组成的凸包。

• cout_mat.cpp: 使用cout 来输出各种格式化的 Mat 对象。

• create_mask.cpp: 演示如何创建黑白掩码图像。

• dbt_face_detection.cpp: 基于检测的人脸跟踪代码。

• delaunay2.cpp: 通过鼠标交互式地生成 Delaunay 三角形。

• demhist.cpp: 演示直方图的用法。

• descriptor_extractor_matcher.cpp: 演示 features2d 检测框架的用法。

• detection_based_tracker_sample.cpp: 与 dbt_face_detection.cpp 类似。

• detector_descriptor_evaluation.cpp: 评估各种特征检测器和描述子。

•detector_descriptor_matcher_evaluation.cpp:评估各种特征检测器和匹配器。

• dft.cpp: 演示一幅图像的离散傅里叶变换。

• distrans.cpp: 显示边缘图像的距离变换值。

• drawing.cpp: 演示绘画和文字显示功能。

• edge.cpp: 演示Canny 边缘检测。

• em.cpp: 对随机生成的数据点进行 EM 聚类。

• fabmap_sample.cpp: 演示 FAB-MAP 图像检索算法。

• facerec_demo.cpp: 人脸识别。

• fback.cpp: 实时的Farneback 光流跟踪。

• ffilldemo.cpp: 演示 floodFill() 像素填充算法。

• filestorage.cpp: 演示序列化到外部文件，如yml、xml等。

• fitellipse.cpp: 将轮廓点匹配到椭圆。

• freak_demo.cpp: 演示 FREAK 特征值的用法。

• gencolors.cpp: 演示 generateColors()。

• generic_descriptor_match.cpp: 基于 SURF 的两幅图像间的匹配。

• grabcut.cpp: 演示GrabCut 分割算法。

• houghcircles.cpp: 用霍夫算法检测圆。

• houghlines.cpp: 用霍夫算法检测直线。

• hybridtrackingsample.cpp: 混合跟踪算法（Hybrid Tracker）的演示。

• image.cpp: 来回转换cv::Mat 和 IplImage。

• image_alignment.cpp: 演示 findTransformECC() 函数。

• image_sequence.cpp: 使用 VideoCapture 对象读取序列帧。

• imagelist_creator.cpp: 创建图像列表到 xml 文件。

• inpaint.cpp: 使用鼠标交互地进行图像修补。

• intelperc_capture.cpp: Intel 感知计算设备相关的函数。

• kalman.cpp: 使用卡尔曼滤波进行二维跟踪。

• kmeans.cpp: Kmeans 聚类算法的演示。

• laplace.cpp: 拉普拉斯边缘检测。

• latentsvm_multidetect.cpp: latentSVM 检测器。

• letter_recog.cpp: 字母识别。

• linemod.cpp: 基于OpenNI 的体感设备应用。

• lkdemo.cpp: 演示Lukas-Kanade光流法。

• logpolar_bsm.cpp: 演示 LogPolar 盲点模型。

• lsd_lines.cpp: LSD 线段检测。

• matcher_simple.cpp: SURF 特征检测。

• matching_to_many_images.cpp: 一对多的特征检测。

• meanshift_segmentation.cpp: 演示基于均值漂移的色彩分割函数——meanShiftSegmentation()

• minarea.cpp: 寻找最小包围盒、包围圆

• morphology2.cpp: 形态学图像处理

• npr_demo.cpp: 演示各种非真实感渲染效果

• opencv_version.cpp: 输出 OpenCV 库的版本号

• openni_capture.cpp: 演示 OpenNI 相关的体感设备

• pca.cpp: 基于 PCA 的人脸识别

• peopledetect.cpp: 基于 cascade 或 hog 进行物体（人）检测

• phase_corr.cpp: 演示 phaseCorrelate() 函数

• points_classifier.cpp: 演示各种机器学习算法

• segment_objects.cpp: 实时地在视频或相机画面中检测前景物体

• select3dobj.cpp：在一个有标定棋盘的桌子上，使用3D Box标记一个对象，在所有序列帧中，只要照相机可以看到棋盘，就可以跟踪对象，并用Box分割对象

• shape_example.cpp: 比较并检索形状

• shape_transformation.cpp: 用 SURF 特征值检测形状并进行变换

• squares.cpp: 检测图像中的方块形状。

• starter_imagelist.cpp: 加载一个ImageList（由imagelist_creator.cpp产生）

• stereo_calib.cpp: 双目视觉的标定

• stereo_match.cpp: 计算左右视觉的图像的差异，生成点云文件。

• stitching.cpp: 演示图像拼接算法。

• stitching_detailed.cpp: 演示更多参数的图像拼接算法。

• train_HOG.cpp: 训练 HOG 分类器

• tree_engine.cpp: 演示如何使用不同的决策树和森林包括Boosting和随机树

• videostab.cpp: 演示 videostab 中各个参数的用法。

• watershed.cpp: 演示著名的分水岭图像分割算法。
————————————————
版权声明：本文为CSDN博主「Stone_石头」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/stone_wang_mz/article/details/94399840