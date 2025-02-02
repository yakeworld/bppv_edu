# 项目名称：新医科背景下问题导向的BPPV课程教学设计

## 前言
希望每一个新医科背景下培养的医师，都能够理解和掌握本项目所需要的知识。也希望老模式下培养的医师，努力去学习和掌握本项目所需要的知识。
本项目也为眩晕研究者/教育者提供交流平台和参考。


## 立项依据：（项目的意义、现状分析）
“新医科”建设是适应我国医药卫生体制改革和高等教育质量革命需要提出的创新举措。2018年8月，中共中央在全国教育大会之前半个月印发的文件中指出“高等教育要努力发展新工科、新医科、新农科、新文科”，首次正式提出“新医科”概念。同年10月，教育部、国家卫生健康委员会、国家中医药管理局启动实施《卓越医生教育培训计划2.0》，对“新医科”建设进行全面部署。教育部高教司司长吴岩指出：“加强新医科建设，一是理念新，实现从治疗为主到生命全周期、健康全过程的全覆盖；二是背景新，以人工智能、大数据为代表的新一轮科技革命和产业变革扑面而来；三是专业新，医工理文融通，对原有医学专业提出新要求，发展精准医学、转化医学、智能医学等医学新专业[^3]。面对新的健康需求和医学人才培养时代要求，实现医学从“生物医学科学为主要支撑的医学模式”向以“医文、医工、医理、医X交叉学科为支撑的医学模式”的转变[^4][^5]，具有十分重要的理论意义和现实意义。由此可见，新医科的建设和发展已然成为深化高等院校教育改革，满足社会产业、医学发展的现实要求。医学院校将在大学综合学科优势引领下，积极推进医理工文的深度交叉融合，以培养理工基础厚实、临床专业精深、具有全球视野和人文情怀的医学科学家和卓越医生为培养目标。作为我国医学教育供给侧结构性改革的新举措，“新医科”建设目前更多停留在理念和专业层面，仍面临不少现实的瓶颈和约束。
“在教学方式上，以教师为中心的传统授课方式仍是主流。学生评价方式普遍采取纸笔考试方法，偏重知识记忆。“[^10]学生的学习更多关注现有知识，忽视知识应用和自主获取知识能力培养，对新一轮科技革命带来的新技术掌握不够，医学生岗位胜任力培养不适应行业发展需求。在新医科人才培养目标的指引下，加强课程建设，提高课程质量，是当前深化医学研究生教育改革重要和紧迫的任务。
良性阵发性位置性眩晕 (benign paroxysmal positional vertigo, BPPV) 是最常见的外周性眩晕疾病, 约占前庭性眩晕患者的20%~30%。目前被广泛接受的理论是BPPV是由囊斑上脱落的耳石颗粒移动至半规管内而引起。通过特定的头位改变使得耳石在特定半规管内在重力作用下发生沉降，其流体力学效应刺激壶腹嵴诱发眩晕眼震，根据眼震特定可以判断病变半规管及耳石位置。通过一系列的头位改变使得移位的耳石回复到椭圆囊中，可以使得疾病得到治疗。
新医科背景下，BPPV的教学，牵涉到医学影像分割和处理，半规管解剖特点和空间方向，前庭生理机制，前庭功能评估，三维空间旋转理解，流体力学机制，诊疗方法评估，眼震分析评估，耳石定位，物理拟真观察，智能诊疗设备开发等内容。BPPV课程内容，涉及多个学科和专业，交叉跨度大，综合性强，对教学带来一定难度。但这也是培养“交叉复合型人才”所必须面对的问题。
为此，本研究在教育部实施“新医科”建设的教育改革背景下，对BPPV专业课程改革进行思考和设计，提出相应的教学实践措施，注重知识更新和交叉融合，探索培养素质高、创新能力强的复合型医科人才。

## 项目实施方案及实施计划

### 1.具体改革内容、改革目标和拟解决的关键问题
传统BPPV教学局限于医学领域如病因病理、发病机制、临床表现、诊断和鉴别诊断以及治疗。“新医科”建设注重交叉融合，因此课程从临床应用和研究角度，引出问题，通过生物工程技术等交叉学科知识来解决问题，培养学生医工结合的学习思维。课后作业，通过学生主动思考临床需求问题，激发他们对医学、工程知识主动交叉、主动融合的热情。在深入理解“新医科”建设内涵的前提下，我们基于问题导向，开放式课堂，围绕6个问题进行了相应的教学改革设计，以期提升教学水平。
#### 问题1:如何测量半规管空间方向
半规管模型和半规管空间方向，对于理解BPPV的发病机制和诊疗手法，至关重要。为测量半规管空间方向，首先需要分割半规管模型，并且需要确立立体空间坐标系，然后确定半规管平面，从而进行编程计算。从而引出子问题：
##### 1.1 如何分割半规管模型
手动分割，半自动化分割，基于深度运算的自动化分割。
通过运用3D Slicer软件，Meshlab软件，python编程等，可以加强对医学图像本质的认识，并了解和掌握人工智能在图像处理中的应用。
##### 1.2 如何确立立体空间坐标系
了解法兰克福平面，并探索其他平面如半规管眼底平面。
##### 1.3 如何确立半规管平面
三点确定平面，并探索其他方法，以及通过编程自动化获取半规管中心点连线。
##### 1.4 测量半规管空间方向
引入平面的法向量概念，方向角，四元数，欧拉角。
#### 1.5 膜半规管、壶腹嵴空间方向
临床CT和MRI检查无法显示膜迷路结构，可以通过颞骨切片、磁共振显微成像、微CT等技术研究膜半规管。
问题1的解决涉及医学影像学，数学，python编程，以及医学影像处理软件运用和人工智能知识运用。

### 问题2: 如何旋转内耳使得特定半规管平面和坐标平面平行
在BPPV的诊疗操作中，常常需要转动头部使得后半规管和矢状面平行，外半规管和水平面平行。不同于二维平面的旋转，三维空间的旋转需要围绕特定的旋转轴才能一次旋转到目标位置。所以通常认为后半规管和矢状面夹角是45都，头部向右侧旋转45°，右侧后半规管和矢状面平行，这种看法，并不准确。通过半规管平面方程，确立其法向量，计算旋转的四元数，可以转换成欧拉角，至少有12种欧拉角方案。学习过程可以培养三维空间想象力，掌握三维空间旋转编程知识。
### 问题3：如何建立BPPV仿真模型
分析BPPV诊疗方法，研究其发病机制，建立BPPV仿真模型是十分必要的。可以探索制作简单的模型，通过3D打印模型，实现计算机物理仿真等，培养通过医工结合交叉知识运用，解决临床和科研问题的能力。基于Blender平台，使用Bullet物理引擎，实现BPPV物理拟真平台，观察和分析BPPV诊疗过程耳石运动。进一步可探索建立壶腹嵴生物力学模型。
学习过程可以培养3D模型制作和打印，opencad，freecad，blender等开源软件的操作，以及物理仿真知识。进一步开放性的探索，如真实世界的耳石运动观察，需要同步采集头位信息，并实现同步物理拟真，是当前的前沿科学技术和科学问题。
### 问题4：如何通过观察眼震确定病变半规管
根据前庭生理知识，我们知道两侧外半规管以及一侧后半规管和对侧上半规管构成共轭平面，一侧的半规管兴奋相当于对侧的半规管抑制，其眼震表现类似。虽然兴奋性刺激强于抑制性刺激，但二者有交叉。理论上，根据眼震特点，只能判断共轭平面。由此，引出多次眼震观察，眼震记录，眼震分析，以及自动化诊断。开放性探索，激发医工交叉解决临床问题的热情。
### 问题5: 诊疗方法合理性分析
通常不同半规管BPPV均有多种诊疗手法，除了根据循证依据，如何通过物理仿真试验分析诊疗手法合理性。通过耳石运动观察，掌握诊疗操作和原理，同时引导进行诊疗手法改良和创新。
### 问题6:标准化智能诊疗
视频眼震记录仪，智能化诊疗设备。开放性探索，激发研究热情。

## 实施方案、实施方法、具体实施计划（含年度进展情况）及可行性分析
由于教学内容涉及多个专业领域知识，为方便学习，基于github/gitlab建立项目，制定指南和任务。核心内容配备PPT语音讲解，开放性内容基于互联网学习。
针对各个问题，提供相应素材，具体实现例子和代码，并制定任务。



[^3]: 吴岩．新工科：高等工程教育的未来：对高等教育未来的战略思考[J]．高等工程教育研究，2018(6):1-3．


[^4]: 顾丹丹，钮晓音，郭晓奎，等．“新医科”内涵建设及实施路径的思考[J]．中国高等医学教育，2018(8):17-18.

[^5]: 何珂，汪玲．健康中国背景下“新医科”发展战略研究[J]．中国工程科学，2019,21(2):98-102. 
[^10]: 施晓光，程化琴，吴红斌．我国新一轮医学教育改革的政策意义、诉求与理念[J]．中国高等教育，2018(15):61-63．
 
 
