

吴曙智， 李熹， 郑炎焱， 林一均， 杨晓凯
 |||
|--|--|
| 【作者机构】 | [温州市人民医院神经内科温州医科大学温州市第三临床学院](http://qikan.chaoxing.com/jourcompany?compyids=625149) |
| 【来    源】 | [《中华耳科学杂志》](http://qikan.chaoxing.com/mag/infos?mags=ea15bb11cfca24247c43bf11651bccf9) 2017年第6期 P732-736页 |
| 【分 类 号】 | R445.2;\|R764 |
| 【分类导航】 | [医药、卫生](http://qikan.chaoxing.com/s?sw=classfy(R)&size=20)->[临床医学](http://qikan.chaoxing.com/s?sw=classfy(R4)&size=20)->[诊断学](http://qikan.chaoxing.com/s?sw=classfy(R44)&size=20)->[影像诊断学](http://qikan.chaoxing.com/s?sw=classfy(R445)&size=20) |
| 【关 键 词】 | [内耳](http://qikan.chaoxing.com/jourkeyword?sw=%E5%86%85%E8%80%B3) [三维](http://qikan.chaoxing.com/jourkeyword?sw=%E4%B8%89%E7%BB%B4) [分割](http://qikan.chaoxing.com/jourkeyword?sw=%E5%88%86%E5%89%B2) [半规管](http://qikan.chaoxing.com/jourkeyword?sw=%E5%8D%8A%E8%A7%84%E7%AE%A1) |
| 【基    金】 | 温州市科技局基金资助(项目编号:Y20160286) 温州市重大科技专项基金资助(项目编号:ZS2017020) |
| 【摘    要】 | 目的为了获取独立的内耳三维模型,探讨一种半自动、快速的内耳分割方法。方法将MRI图像导入3D slicer软件,基于Otsu法,采用半自动分割内耳,并结合meshlab软件进行内耳后期精细处理。结果对30例MRI影像数据进行分割,一侧内耳完成半自动分割仅需3钟左右,内耳三维模型图像清晰,内耳信息保留完整。结论Otsu法进行内耳半自动分割操作简单、快捷,内耳模型结构完整,三维成像效果好。|
|全文下载| [pdf下载](http://qikan.chaoxing.com/goread?aid=7209&dxid=100253678108&pkey=0&datatype=1&sid=43&ssid=&d=7f54d8e847769480e95942aadf58a56916994b4ee7ccfcfe6ff5487c59260134e8e21d61b9938a007cc4c604baa8308d3f699cbc6856caa863e4a732f6a1cdcca565eafbc1fc4f8b12234821bcf64052&sort=0&isjx=&magid=320910011420&date=2017&title=&sqnum=&apistrclassfy=0_16_7,0_16_15&flid=161) |

# 基于Otsu法的内耳MRI图像三维快速分割的研究
吴曙智 李熹 郑炎焱 林一均 杨晓凯*

温州市人民医院神经内科，温州医科大学温州市第三临床学院（温州325000）

**【摘要】**目的为了获取独立的内耳三维模型，探讨一种半自动、快速的内耳分割方法。方法将MRI图像导入3D slicer软件，基于Otsu法，采用半自动分割内耳，并结合meshlab软件进行内耳后期精细处理。结果对30例MRI影像数据进行分割，一侧内耳完成半自动分割仅需3钟左右，内耳三维模型图像清晰，内耳信息保留完整。结论Otsu法进行内耳半自动分割操作简单、快捷，内耳模型结构完整，三维成像效果好。

**【关键词】**内耳；三维；分割；半规管

内耳，又称为迷路，包括骨迷路和膜迷路，位于颞骨岩部骨质内，其结构精细而复杂，对其解剖断面的研究较多，但大多基于组织切片观察，缺乏空间方向信息[^1] 。

随着医学影像学的发展，临床CT和MRI检查可以显示骨迷路结构，许多学者利用计算机图像处理技术对内耳进行了三维可视化、几何形状分析，以建立三维可视的内耳模型。一方面可以更好地观察内耳的形态、空间位置关系等，另一方面对于临床常见疾病，如耳石症中耳石复位演示，人工耳蜗植入手术的导航，内耳三维模型在医学教学领域应用等均有很大帮助[^2] 。

内耳三维重建首先需要对内耳结构进行分割，但手动分割繁琐耗时，而自动化分割依然是研究的热点和难点。在内耳相关疾病的研究中，如三维重建内耳进行BPPV耳石复位的精准治疗，人工耳蜗植入手术的患者筛选、手术禁忌症排除等方面有指导作用，一种快速、精确的内耳分割方法就显得非常重要，而手动分割不能满足临床需求[3-4]。

而本研究采用的Otsu法分割技术能较为有效的解决内耳分割中的困难。OTSU算法也称作最大类间方差法[^9] ，其最大的优点是算法简单，可以获取最佳阈值将图像分割为前景和背景两个部分[^5] 。基于此原理，运用Otsu法可以有效的将内耳部分和背景图像分开，在3D Slicer软件中可以多种途径调用，从而实现内耳半自动化分割，探讨其步骤实现和分割结果[^6] [^7] 。

## 1 材料和方法

### 1.1 资料选择

选择在2015-2017年就诊于温州市人民医院的患者MRI内耳扫描影像资料，共30例，男11例，女19例，年龄在5-66岁，平均年龄34岁，其中18周岁以10下例，18周岁以上20例。入组患者中正常无耳源性症状者13例，有耳源性疾病者17例，其中BPPV患者7例，梅尼埃病3例，中耳炎患者4例，突发性耳聋2例，先天性耳聋1例。

入选标准：1.内耳MRI检查没有发现结构异常，2.内耳显示清晰，没有伪影。3.各种病因行内耳MRI检查者，排除内耳结构异常者。

排除标准：1.存在局部病变可能影响半规管解剖结构2.存在头颅结构异常。

仪器为SIEMENS公司1.5T高场强磁共振系统，标准头线圈，应用三维稳态构成干预序列（3D constructive interference insteady state，3D-CISS），扫描参数为：TE2.7 ms，TR6.0 ms，层厚0.7 mm ，matrix（矩阵）256×192，FOV135×180。

### 1.2 图像处理流程

1.2.1 数据导入和管理

3D Slicer作为开源医学图像处理平台在临床研究领域广泛使用，主要用作医学影像分割和可视化，为以下操作默认工作平台[^8] 本研究采用的是3D Slicer 4.6版本（来源网址：https://www.slicer.org）。从医学影像信息系统导出原始图像资料保存DICOM格式图像，导入到3D Slier软件，读取3D-CISS序列[9-10]。

1.2.2 Otsu图像分割

选择Otsu Threshold Image filter模块，在Input Volume中选择导入的MRI原始图像资料，点击ap⁃ply按钮，获得二值化图像。

![](https://upload-images.jianshu.io/upload_images/10716757-94fc98aedc29f782.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图1 Otsu法分割内耳效果图
Fig.1 The effect graphs of Otsu method on the segmentation of inner ear

左侧为Segment editor模块界面，右上为三维重建内耳，右下图从左到右分别为横断面、矢状面、冠状面。图中红色标记为右侧内耳，绿色标记为左侧内耳。

1.2.3 内耳模型处理

选择Editer中的paint Effect选项，并通过勾选Label中相应颜色，在Red Slice Only视窗中分离出与内耳结构相连的组织。选择Change Island effect as点击内耳轮廓图像位置，选择Make Model effect点击apply，生成三维内耳模型。选择Sementations模块中的Import，完成导入切割后的内耳模型。

1.2.4 内耳表面模型的精细处理。

选择Segment Editor模块利用其中的Scissors选项，选择合适的inensity range，默认设置200，对导入的内耳模型精细化处理。将处理好的内耳模型保存，格式选择为stl。

1.2.5 内耳模型3D合并。

打开Meshlab软件，将之前处理后的内耳模型导入该软件中，点击Filters的子选项Flatten Visible Layers，点击apply按钮，内耳图像将自动进行合并[^11] 。

1.2.6 内耳模型3D精细处理

在Meshlab软件中选择Filters中的Cleaning and Repairing选项，选择Remove Isolated Pieces(wrt Diameter)，点击Apply，可以清除碎片。再选择mesh layer模块中的Split in connected compo⁃nents，可以根据相连性进一步将模型中不必要的网格结构分离出来，选择双侧内耳，点击Merged Mesh模型，保存在Export mesh as，格式选择stl，完成内耳分割[^12] 。

## 2 结果

3D Slicer软件除了有Otsu Threshold Filter模块可以直接使用，也可以用python语言编程调用Sim⁃pleITK模块Otsu Multiple Thresholds算法或者Otsu Threshold算法，可以减少按键选择步骤，加快操作速度。

Otsu法分割获取的内耳模型，其耳蜗部分比较完整和独立。但是由于影像数据质量不同，其分割结果也有所不同。部分数据根据生成的二值图像即可获取完整内耳模型，部分数据需要简单手工处理即在2-3个层面擦除耳蜗和周边粘连部分，还有部分数据半规管部分需要精细化处理，耗时有所增加[^13] 。

3D Slicer软件自带的Segment Editor模块Scis⁃sors功能，3D界面操作，所见即所得，不仅可以根据阈值对选择视野部分进行填充，还可以进行剪切删除，在Otsu分割基础上进行加工操作简便，是模型3D精细处理的有效工具[^14] 。

使用上述方法分析30例影像数据，一侧内耳完成半自动分割仅需3钟时间左右，图像可以清晰显示完整内耳结构，和周围组织结构分开并独立，并且内耳结构完整，尤其耳蜗部分比较完整和独立（图2）。本方法操作简便，在临床工作中有很大使用价值。

![](https://upload-images.jianshu.io/upload_images/10716757-033fa3706d3de3a1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图2 Otsu法分割获取的内耳模型
Fig.2 The model of Otsu method on the segmentation of inner ear

虽然在3D Slicer模块中也可以手工进行模型的修补和清理，但是使用MeshLab软件提供的一系列工具来进行模型的清理更加方便和快捷。分割的内耳模型表面成像和内耳体素成像显示的表面结构高度一致，提示分割效果较好。而体素模型较表面模型大，三维重建可以显示核心部的内耳以及周边的阴影。黄色显示为体素成像，蓝色显示为表面成像，如图所示内耳三维图像完全吻合（图3）。

![image](https://upload-images.jianshu.io/upload_images/10716757-afe2245713cd0c75.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图3 内耳表面成像与体素成像。A图为左耳、B图为右耳。
Fig.3 Inner ear surface imaging and Voxel Imaging.FigureAis left ear,figure B is right ear

3D-CISS序列内耳原始数据较大，容量大约在12-15MB，经3D-slicer处理后的两侧内耳三维模型的文件（STL格式）容量为400-715kb，模型容量较小，便于储存。

同时本研究对十八周岁年龄为界限，对成年人和未成年人内耳体积大小进行观察，基于Otsu法分割后内耳模型，利用3d-slicer软件中的Infama⁃tion模块计算出内耳模型体积，但因作者所在医院为成人综合性医院，儿童患者病例数较少，故因两组例数差别较大，未能进行统计学分析。将在以后的研究中再进一步完善。但通过两组初步观察，成年人（18周岁以上）与未成年人（18周岁以下）分割后内耳模型的面积及体积总体大小可能存在一定差异，所有30例入组者内耳模型体积均数为354.4±47.7mm³。

表1 十八周岁以下与十八周岁以上内耳分割后模型体积比较
Table1 Comparisonofthevolumeoftheinnerearmodelabout underandovereighteenyearsofage

![image](https://upload-images.jianshu.io/upload_images/10716757-daaf9230666382dd.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 3 讨论

内耳自动化分割一直是研究的热点和难点，尤其是半规管和耳蜗部分的最佳分割阈值并不一致，目前缺乏公认有效的自动化分割算法。基于先验知识的分割方法，理论上分割效果好，但其实现较复杂和困难。

手动分割是最常用的手段，但是由于内耳结构精细、复杂，本身为曲面结构，断面解剖图像变换较大，这需要相关操作者对内耳的解剖结构以及内耳MRI影像特点充分了解，极为考验操作者的能力。同时由于手工操作基于人为的因素太多，在切割过程中，难以避免的造成内耳旁结构剔除的不完整，分割获取的三维模型表面常粗糙不光滑[^15] 。

有学者曾利用3D Slicer的Volumeclip模块根据ROI进行体裁剪，但是其对操作要求仍高，尤其是对内耳解剖结构空间方位要非常熟悉，最重要的是分割耳蜗部分时存在较大的局限性，耳蜗部分和周围组织常有黏连，难以分割。

为解决上述的分割难点，可以先进行自动化分割获取内耳三维图像，在此基础上进行直观的手动操作，这将会是一种有效的方法[^16] 。Otsu算法是由日本学者OTSU于1979年提出的一种对图像进行二值化的高效算法，也称作最大类间方差法[^17] ，在算法实现上通常采用等价的最小化类内方差，其最大的优点是算法简单，可以获取最佳阈值将图像分割为前景和背景两个部分。基于此原理，运用Otsu法可以快速将内耳部分和背景图像分开，在3D Slicer软件中可以多种途径调用。

基于Otsu法分割的耳蜗成像光滑完整，再通过Change Island Effect点选内耳部分，即可判断内耳和周边组织有无粘连。解剖结构不熟悉，可以3D成像后直观观察和指导擦除耳蜗和周边粘连部分，熟练后简单观察和操作2-3个层面即可[^18] 。对半规管分割的修正，使用Scissors功能操作非常直观，统一旋转内耳到指定方位，保证操作的一致性。相对于其他分割方法，由于Otsu法分割获取的耳蜗结构比较稳定，半规管部分经过观察和直观的精细化处理，所得图像质量较高，保留内耳信息完整。使用Meshlab软件对模型文件的进一步清理，是模型分享、3D打印和建立统计形状模型的必要步骤[^19] 。图像分割效果的判断较为困难，一般为专家根据其经验的判断加以评估，而通过体素和表面混合成像进行比较，可以直观的评估分割的准确性，客观性较好，误差小。被认为是一种有效的评估图像分割的方案。

内耳三维可视化具有重要的意义，在临床在可以有较广泛的应用。例如在进行人工耳蜗术前的评估。目前多层螺旋CT虽然可以较好的显示内耳骨迷路等骨性结构，但对内耳膜迷路显像效果不佳，对某些人工耳蜗植入术的禁忌症，如耳蜗发育异常，双侧听神经缺如等，在诊断上较为困难。而MRI水成像技术通过内、外淋巴液的分布形态来显示膜迷路形态，以此提供内耳的解剖信息，对人工耳蜗手术患者病例选择、手术导航等有重要诊断意义。但MRI图像三维重组后因为所得图像同时显示了内耳邻近组织，使得内耳组织与其他组织相互重叠，难以独立的显示内耳结构，对临床诊断和治疗带来了困扰。同时由于目前的MR三维重组多为影像科工作人员手工操作，不仅费时、费力，并且对操作者要求较高，操作难度大，而效率较低[^19][^20]。本研究采用的基于Otsu法的内耳半自动三维可视化，简化了分割操作步骤，在此基础上进行的手动操作也是比较直观，学习推广较容易。

同时，本文作者主要从事为眩晕症的研究，在我们前期的研究中发现，半规管空间方向存在较大的个体差异性[^3][^7]，可能对BPPV的诊断和复位产生影响，所以提出了根据患者的内耳影像数据进行三维内耳重建进行BPPV精准治疗，而掌握一种快速、准确的内耳三维重建技术，将为临床治疗提供了基础。并且为后续研发良性阵发性位置性眩晕智能诊疗设备，可以根据患者内耳影像数据进行内耳自动化分割和三维重建，通过校准方式确定膜迷路空间方向，进行个体化的诊断手法和复位手法，所以内耳三维重建在BPPV的诊断和治疗中也有一定的实际意义[^12] 。同时本研究比较了成年入组者（年龄18周岁以上），与未成年组（18周岁以下）在内耳分割模型体积的差异性，因本研究主要为改良内耳分割中的难点，以达到对内耳影像学图像的精确处理，故在病例入组年龄上未加以限制，使得两组病例数量上差别较大，未能进行统计学分析，将在以后的研究中继续加以完善。但是由于Otsu的算法实现较简单，还不能完全解决半规管和耳蜗部分的最佳分割阈值并不一致问题。Otsu算法存在多种改良，但包括多级阈值算法（Multi Otsu method）依然不能解决这个问题。多种分割算法的综合应用或者基于先验知识的分割方法会是下一步的研究方向[^17] [^20] 。

**参考文献**

[^1]: Fedorov A，Beichel R，Kalpathy-Cramer J，et al．3D Slicer as An⁃image Computing Platform for the Quantitative Imaging Network.[J]Magn Reson Imaging，2012，30：1323-1341．

[^2]: 林有辉林少莲叶胜难等.听力学检测和内耳磁共振成像在梅尼埃病诊断中的作用[J].中华耳科学杂志,2017,15(3):290-.Lin YH，Lin SL,Ye LN et al.The Role of Audiology and Ear Mag⁃netic Resonance Imaging in Diagnosis of Meniere's Disease[J].Chinese Journal of Otology,2017,15(3):290-.

[^3]: 杨晓凯．磁共振显微成像三维重建显示成人尸体膜半规管．中国耳鼻咽喉头颈外科，2015，22 315-316．Yang XK，Three-dimensional Reconstruction of the Adult Cadav⁃er Membrane Semicircular Canal with Magnetic Resonance Mi⁃croscopy[J].Chin Arch Otolaryngol Head Neck Surg,2015，22 315-316．

[^4]: Lane JI，Witte RJ，Henson OW，et al． Imaging Microscopy of the Middle andInner Ear:Part II:MR Microscopy［J］.Clin Anat，2005，18(6):409-415．

[^5]: 熊彬彬;吴子明刘兴健等良性阵发性位置性眩晕的临床特征分析[J].中华耳科学杂志,2012,10(2):208-208.Xiong BB,Wu ZM,Liu XJ,et al.Analysis of Clinical Characteris⁃tics of Benign Paroxysmal Positional Vertigo[J].Chinese Journal of Otology,2012,10(2):208-208.

[^6]: 庞全,苏佳,段会龙.基于四叉树和交叉熵的面向对象图像分割方法[J].浙江大学学报:工学版,2004,38(12):1615 1618.Pang Q,Su J,Duan HL,et al.An Object Oriented Image Segmenta⁃tion Method Based on Four Forked Tree and Cross Entropy[J].Journal of Zhejiang University:Engineering Edition,2004,38(12):1615 1618.

[^7]: 孙伟，张彩明，杨兴强．Marching Cubes算法研究现状．计算机辅助设计与图形学学报，2007，19：947-952．Sun W,Zhang CM,Yang XQ,et al.Marching Cubes Present Situa⁃tion of Algorithm Research[J].Journal of Computer-Aided De⁃sign and Computer Graphics|J Comput-Aid Desig Comput Graph,2007，19：947-952．

[^8]: 杨晓凯，吴曙智，陈晓素，基于内耳体素模型的膜迷路三维可视化[J]《解剖学报》2017，48（2）：170-174.Yang XK,Wu SZ,Chen XS et al.Three-dimensional visualization of membrane labyrinth based on the inner ear voxel model[J]Ac⁃ta Anatomica Sinica(Acta Anat Sin)2017，48（2）：170-174

[^9]: 翟方兵．内耳MRI医学图像的自动分割及应用．大连：大连理工大学，2012.Zai FB.Automatic Segmentation and Application of MRI Medical Images in Inner Ear[J].Da Lian:Dalian University of Technology,2012.

[^10]: 刘怀军,李书玲,黄勃源,等,内耳系统磁共振解剖及仿真内窥镜研究[J].中国临床医学影像杂志,2004,15(1):4-7.Lin HJ,Li SL,Huang BY et al.Magnetic Resonance Anatomy and Simulation Endoscope Study of the Inner Ear System[J].Journal of China Clinic Medical Imaging,2004,15(1):4-7.

[^11]: 李英,谢敬霞,刘剑羽.3D-CISS序列在内耳及内听道磁共振成像中的应用[J].中国医学影像技术,2003,19(4):415-417.Lin Y,Xie JX,Liu JY.The Application about 3D-CISS of Inner Ear and Internal Auditory Canal in Magnetic Resonance Imaging[J].Chinese Journal of Medical Imaging Technology,2003,19(4):415-417.

[^12]: 杨燕珍黄静辉余怀生.Epley加Semont联合手法复位治疗后半规管良性阵发性位置性眩晕[J].中华耳科学杂志,2010,8(1):86-86.Yang YZ,Huang JH,Yu HS,et al.Treatment of Posterior Semicircu⁃lar Canal Benign Paroxysmal Positional Vertigo Using Combined Epley-Semont Maneuver[J].Chinese Journal of Otology,2010,8(1):86-86.

[^13]: 李晶兢余力生夏睿等7.0T磁共振成像观察耳后给药促进药物进入内耳的可行性[J].中华耳科学杂志,2012,10(2):144-144.LI JJ,YU LS,Xia R,et al.Feasibility Study of Inner Ear Drug Deliv⁃ery Via Post-auricular Injection Using 7.0 Tesla MRI[J].Chinese Journal of Otology,2012,10(2):144-144.

[^14]: Rabbitt RD,Breneman KD,King C,et al.Dynamical Displace⁃ment of Normal and Detached Semicircular Canal Cupula.[J].As⁃soc Res Otolaryngol,2009,10(4):497

[^15]: Kassemi M,Deserranno D,Oas JG.Fluid-Structural Interaction⁃sin the Inner Ear.[J]Ann N Y Acad Sci,2004,1027:360-3

[^16]: Salviroonporn P,Robatino,Zahajszky J,et al.Real-Time Iinterac⁃tive Three-Dimensional Segmentation[J].Academic Radiology,1998,5(1):49 56.

[^17]: 杨晓凯，郑炎焱，吴曙智，等.基于磁共振数据的三维半规管建模空间方向测量［J］.解剖学报，2016，47(2):238-242．Yang XK,Zheng YY,Wu SZ,et al.Spatial Direction Measurement of 3D Semicircular Tube Modeling Based on Magnetic Resonance Data［J}.Acta Anatomica Sinica(Acta Anat Sin),2016，47(2):238-242．

[^18]:石丽亚戴朴韩东一等计算机辅助内听道三维重建[J].中华耳科学杂志,2004,2(1):57-57.Shi LY,Dai P,Han DY,et al.Computer Aided Tthree-Dimensional Reconstruction of the Internal Auditory Canal[J].Chinese Journal of Otology,2004,2(1):57-57.

[^19]: Fedorov A，Beichel R，Kalpathy-Cramer J，et al．3D Slicer as an Image Computing Platform for the Quantitative Imaging Network.[J].Magn Reson Imaging，2012，30：1323-1341．

[^20]: 杨静雅田广永黄文华等3-D颞骨模型的制作与应用[J].中华耳科学杂志,2015,13(2):369-369.Yang JY,Tian Gy,Huang WH,et al.Manufacture and Application of Three-dimensional Prototyped Model of Temporal Bone[J].Chinese Journal of Otology,2015,13(2):369-369.

3D Visualization of Inner Ear Based on Otsu Method

WU Shuzhi,LI Xi,ZHENG Yanyan,LIN Yijun YANG Xiaokai
Department of Neurology,Third Clinical Institute Affiliated to Wenzhou Medical University;Wenzhou People’s Hospital,Wenzhou,China

**Corresponding author:**YANG Xiaokai Email:yakeworld@126.com

**【Abstract】**Objective To report a semi-automatic and fast segmentation method for the purpose of obtaining an independent 3D model of the inner ear.Methods MRI images were imported and the inner ear was processed by semi-automatic segmentation using the 3D Slicer software and then combined with the Otsu software.The inner ear was finally fine-tuned with the MeshLab software.Results In processing 30 images,segmentation of the inner ear on one side took about 3 minutes using the semi-automatic method,yielding clear three-dimensional images of the inner ear with no loss of information.Conclusion The Otsu method is a simple and fast inner ear semi-automatic segmentation tool for constructing and the inner ear model with good three-dimensional effects.

**【Key words】**Inner Ear；Three-dimensional；Segmentation；Semicircular Canal

Funding information：Science and Technology Foundation of Wenzhou,Grant Number:Y20160286.Science and Technology Major Project of Wenzhou，china(Grant Number：ZS2017020)

The authors report no conflicts of interest

**【中图分类号】**R764

**【文献标识码】** A

**【文章编号】**1672-2922（2017）06-732-5

**DOI:**10.3969/j.issn.1672-2922.2017.06.024

**基金项目:**温州市科技局基金资助(项目编号：Y20160286）温州市重大科技专项基金资助（项目编号：ZS2017020）

**作者简介：**吴曙智，硕士，主治医师，研究方向:眩晕及内耳分割、标准模型建立、三维图像处理

**通讯作者：**杨晓凯，Email:yakeworld@126.com

**（收稿日期：**2017-08-03 审核人：宋跃帅）
