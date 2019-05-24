
# PCB-Design

__Update__ on 2019.5.3

__Project:__ This project is design a PCB as my final homework.

environment: AD2018

---

## Timeline:
Before 2019.5.1
1. My friend give one demo file (红外发射) 

2019.5.1
1. I find in the internet and find a very [good example](http://www.elecfans.com/article/88/131/ctrlsc/switch/2018/20180125623122_a.html), which I want to clone it. And I find it is very hard to find all of those materials and hard to create a good PCB.

---

## Tasks:
Final: 

- 计划书：
目标阐述
关键问题
具体任务
具体方案

- 原理图：
工作原理图
线路原理图

- 成果：
仿真
PCB
元器件参数

Task Arrangement:
1. ~~基本报告~~
2. ~~查找解决方法~~
3. 修改报告
4. 进行简单仿真
5. ~~寻找电子器件进行绘制原理图~~
6. ~~修改PCB~~
7. 再次修改报告

注意：
1. PCB电源没画
Materials:

1. [红外开关电路设计](http://www.elecfans.com/article/88/131/ctrlsc/switch/2018/20180125623122_a.html)

2. [555遥控开关电路图](http://www.elecfans.com/article/88/131/198/2018/20180130626129_a.html)


3. [怎样用NE555制作通用遥控开关](http://www.elecfans.com/d/785135.html)

4. [555三角波发生器](https://www.dianziaihaozhe.com/mulu/guowai/2933.html)

---

## Problems

1. How to create a PCB from sch?

先得新建个PCB文件（File-New-Pcb）；然后保存下，在新建的PCB文件下：Design-Import Changes From PCB_PROJECT1.PRJPCB(Design选项下第二个，PCB_PROJECT1.PRJPCB是新建的PCB文件默认名)；然后会弹出个框Engineering Change Order，依次点最下面的从左至右的1、2两个按钮，如果出现红色的叉，说明原理图有问题，检查下，在按上面的方法继续

2. 生成后怎么办？

布线、覆铜

3. 如何布线和覆铜？
[Altium Designer中如何进行覆铜和网状覆铜？](https://blog.csdn.net/ldcung/article/details/77388291)
[【AD】Altium Designer PCB文件的绘制（下篇：PCB布线和后续）](https://blog.csdn.net/qq_38410730/article/details/80397365)

---

## Result:
![SCH](/img/sch.PNG)

![PCB](/img/pcb.PNG)



---

## How to use:

## Environment
Altium Design 18（用于绘制原理图和PCB）

Multisim 2018（用于仿真）

Latex（用于文章编写和排版）

## 资源
[ProcessOn](https://www.processon.com/diagraming/5b5e80c8e4b08d36229510a8)用于绘制流程图

## 技巧
- Multisim  
multisim中控制开关：DIPSW1  
[NE555 制作呼吸灯 ](http://dxx.qcuwh.cn/wcs/Upload/201611/583d3fd01ed2f.pdf)  


- AD  
[PCB专业术语翻译](https://wenku.baidu.com/view/87ec5d916f1aff00bfd51e4d)  
[Altium Designer——AD画PCB图步骤总结](https://blog.csdn.net/Tang_Chuanlin/article/details/79803575)  
[Altium Designer中如何进行覆铜和网状覆铜？](https://blog.csdn.net/ldcung/article/details/77388291)  
[如何使用Altium Designer 18铺铜？](http://www.icxbk.com/ask/detail/11544.html)   
AD如何统计pin数量：打开原理图→Tools→Parameter  
[Altium Designer覆铜后变为绿色是怎么回事？](https://blog.csdn.net/weixin_42164589/article/details/88853912)  
[如何用Altium Designer画PCB图](https://jingyan.baidu.com/article/363872ec357a206e4ba16f00.html)  
[AD 中设定PCB板尺寸大小的方法](https://blog.csdn.net/mzy202/article/details/54880947)  
[Altium designer如何镜像翻转元件？](https://zhidao.baidu.com/question/365170674728128452.html)  
[Altium Designer——原理图导出元件清单](https://blog.csdn.net/Tang_Chuanlin/article/details/79488115)

- Markdown换行  
两段文字之间敲两个空格符然后换行  


- 清华Latex  
[清华大学学位论文 LATEX 模板](http://mirrors.concertpass.com/tex-archive/macros/latex/contrib/thuthesis/main.pdf)  
[ThuThesis：清华大学学位论文模板](http://mirror.las.iastate.edu/tex-archive/macros/latex/contrib/thuthesis/thuthesis.pdf)  
[Github LaTeX Thesis Template for Tsinghua University](https://github.com/xueruini/thuthesis)

- Latex  
[LaTeX 有哪些「新手须知」的内容？](https://www.zhihu.com/question/30090572)  
[latex分文件编写技巧](https://blog.csdn.net/yanxiangtianji/article/details/13169699)  
Latex插入空白行：~\\\：一行空白
[TeX Live安装指南](https://blog.csdn.net/wr339988/article/details/66611166)

- Latex无法插入目录  
[latex不能生成目录，怎么解决？？](https://zhidao.baidu.com/question/1541025230634017307.html)  
[LaTeX简要教程7:生成目录](http://topspeedsnail.com/g-latex-content-table/)  
[LaTeX 插入pdf文档](https://blog.csdn.net/bendanban/article/details/51850659)  
[latex文字加粗、斜体](https://blog.csdn.net/jminer/article/details/14146939)  
[【LaTeX入门】05、换行、换段、换页、首行缩进等命令](https://blog.csdn.net/xiazdong/article/details/8892105)  
latex中怎么打出百分号： \\%   
[Latex中的cls文件使用](https://blog.csdn.net/owldestiny/article/details/5560347)  
[Latex 编译错误排查的一些经验](https://blog.csdn.net/u012675539/article/details/46272387)  
[Installing TeX fonts](https://www.tug.org/fonts/fontinstall.html)   
[使用VSCode编写LaTeX](https://zhuanlan.zhihu.com/p/38178015)  
[LaTeX技巧932：如何配置Visual Studio Code作为LaTeX编辑器](http://www.latexstudio.net/archives/12260.html)  
[论文写作的又一利器：VSCode + Latex Workshop + MikTex + Git](https://blog.csdn.net/yinqingwang/article/details/79684419)  

- Latex errors  
recipe teriminate with error source: latex workshop(Extension)
---

## Contact
Feel to contact me. My email is richardfeynman180778@gmail.com.
