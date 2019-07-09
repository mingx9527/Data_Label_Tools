# [Data_Label_Tools](https://github.com/mingx9527/Data_Label_Tools)
本文旨在收集整理开源的数据标注工具，方便使用，目前包括Image、Video、Text和Audio 4个方面。文中大部分工具，本人还未亲自测试过，标签或是归档不妥之处也会长期改进！

## Table of Contents
- [1. Image](#Image)
- [2. Video](#Video)
- [3. Text](#Text)
- [4. Audio](#Audio)

## <a name="Image"></a>1. Image
>> ### 1.1 bbox
>> - **[labelImg](https://github.com/tzutalin/labelImg)**
>>      * labelImg是基于python和Qt的跨平台**目标检测**标注工具，操作方便、快捷、实用，应用广泛。
>> - **[bbox-label-tool](https://github.com/puzzledqs/BBox-Label-Tool)**
>>      * bbox-label-tool是基于python的**目标检测**标注工具，实现简单，使用方便，但仅支持单类标注。 
>> - **[LabelBoundingBox](https://github.com/hjptriplebee/LabelBoundingBox)**
>>      * LabelBoundingBox是bbox-label-tool的升级版，能适应多类标注。
>> - **[Yolo_mark](https://github.com/AlexeyAB/Yolo_mark)**
>>      * Yolo_mark是针对**Yolo v2目标检测**的标注工具。
>> - **[FastAnnotationTool](https://github.com/christopher5106/FastAnnotationTool)**
>>      * FastAnnotationTool是一款基于C++和opencv的强大的**目标检测**数据标注工具，支持数据和字母OCR标注，提供多种数据增强功能（尺寸剪切、翻转、旋转、缩放、椒盐噪声、高斯噪声、矩形合并、线提取等），支持带倾斜角度目标标注，实用性极强。
>> - **[od-annotation](https://github.com/hzylmf/od-annotation)**
>>      * od-annotation采用python-flask框架开发，基于B/S方式交互，支持多人同时标注。
>> - **[RectLabel](https://rectlabel.com/)**
>>      * RectLabel即可画框（目标检测）又可画多边形（分割）
>> - **[CVAT](https://github.com/opencv/cvat)**
>>      * CVAT高效的标注工具，图像分类，目标检测，语义分割，实例分割，支持本地部署
>> - **[VoTT](https://github.com/microsoft/VoTT)**
>>      * VoTT 微软发布的Eeb方式部署标注工具，至此图像和视频；支持CNTK，Pascal Voc格式；支持导出TFRecord，CSV，VoTT格式
>> - **[VIA-VGG Image Annotator](http://www.robots.ox.ac.uk/~vgg/software/via/)**
>>      * 图像检测 语义分割 实例分割等;Web方式，也可本地部署；在人脸数据标注上提供了方便操作，人脸数据标注首选 
>> - **[Pixel Annotation Tool](https://github.com/abreheret/PixelAnnotationTool)**
>>      * 语义分割 实例分割标注神器
>> - **[point-cloud-annotation-tool](https://github.com/springzfx/point-cloud-annotation-tool)**
>>      * 3D点云数据标注神器；支持点云数据加载，保存与可视化；支持点云数据选择；支持3D Box框生成；支持KITTI-bin格式数据
>> - **[boobs](https://github.com/drainingsun/boobs)**
>>      * Yolo bbox标注工具；支持输出YOLO/VOC/COCO格式

>> ### 1.2 Mask
>> - **[labelme](https://github.com/wkentaro/labelme)**
>>      * labelme是基于python和Qt的跨平台标注工具，支持**图像分割**标注，操作方便、快捷、实用，应用广泛。
>> - **[pylabelme](https://github.com/wkentaro/labelme)**
>>      * pylabelme是基于python和Qt的跨平台标注工具，支持**图像分割**标注，操作方便、快捷、实用，应用广泛。
>> - **[Labelbox](https://github.com/Labelbox/Labelbox)**
>>      * labelbox是一款多功能数据标注工具，支持**图像分割、图像分类、文本分类**标注，操作方便、快捷、实用，应用广泛。
>> - **[ImageLabel](https://github.com/lanbing510/ImageLabel)**
>>      * ImageLabel是基于Qt和Opencv的**图像分割**标注工具，支持手动绘制轮廓，可利用GrabCut进行半自动标注，方便使用。
>> - **[ImageSegmentation](https://github.com/AKSHAYUBHAT/ImageSegmentation)**
>>      * ImageSegmentation是基于python的**图像分割**标注工具，操作方便实用。
>> - **[opensurfaces-segmentation-ui](https://github.com/seanbell/opensurfaces-segmentation-ui)**
>>      * opensurfaces-segmentation-ui是基于python的**图像分割**标注工具，操作方便实用。
>> - **[labelImgPlus](https://github.com/lzx1413/labelImgPlus)**
>>      * labelImgPlus是labelImg的升级版，支持**图像分割、图像分类、目标检测**标注，操作方便，通用性极强，应用广泛。

## <a name="Video"></a>2. Video
>> - **[video_labeler](https://github.com/hahnyuan/video_labeler)**
>>      * video_labeler是一款基于python的视频**目标检测、目标跟踪**标注工具，轻便实用。
>> - **[vatic](https://github.com/cvondrick/vatic)**
>>      * vatic是一款基于python的视频**目标检测、目标跟踪**标注工具，轻便实用，应用广泛。
>> - **[lane-detection-with-opencv](https://github.com/ckirksey3/lane-detection-with-opencv)**
>>      * lane-detection-with-opencv是一款基于Opencv的视频**车道检测**标注工具，特殊场景标注工具，实用性强。
>> - **[OpenLabel](https://github.com/liushu1231/OpenLabel)**
>>      * Openlabel是一款基于Opencv的视频**目标检测、目标跟踪**标注工具，轻便实用，应用广泛。

## <a name="Text"></a>3. Text
>> - **[brat](https://github.com/nlplab/brat)**
>>      * brat是基于python的**自然语言**标注工具，设计灵活，实用，应用广泛。
>> - **[MarqueeLabel](https://github.com/cbpowell/MarqueeLabel)**
>>      * MarqueeLabel是基于Swift和C的**自然语言**标注工具，设计灵活，实用，应用广泛。

## <a name="Audio"></a>4. Audio
>> - **[audio-annotator](https://github.com/CrowdCurio/audio-annotator)**
>>      * audio-annotator是基于Javascript的**音频**标注工具，它可以实现无形、声谱图、声波进行可视化标注，通用性强，应用广泛。
>> - **[youtube-chord-ocr](https://github.com/henridwyer/youtube-chord-ocr)**
>>      * youtube-chord-ocr是基于python的**音频**标注工具，可以实现将youtube上带有和弦标签的音乐视频转化为带标签的音频文件，应用广泛。
>> - **[MusicSegmentation](https://github.com/torogmw/MusicSegmentation)**
>>      * MusicSegmentation是一种基于matlab的**音乐分割**标记工具，它通过计算谐波和音色分割音乐并标记，应用广泛。
