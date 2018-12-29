**项目名称：幼儿汉语教育APP（移动端）**


**所有人：陈嘉睿**


**[点击此处查看完整产品原型](https://kayuiii.github.io/API_ML_AI/)**


## 产品定位

本产品旨在为2-12岁幼年儿童提供一个入门、学习和提升汉语能力的平台。

## 价值宣言

本产品旨在通过运用人工智能的部分功能（图片识别、语音识别、关键词检索、语音合成）来实现更好的教学效果。

## 用户痛点

* **针对性**

目前市场上多数汉语教育类，都以学校教学、线下补习班补课、线上网课为主，对于学生知识接受程度的反馈不足或是单人针对性辅导能力较弱。而汉语教育APP可以由用户定制其所需课程，由系统及时反馈学习情况，还能针对用户薄弱的知识点加深记忆，是变相的**一对一教学**。

* **便携性**

当代人类从小就开始“一睁眼即是竞争”的生活，每天的大段时间都安排得妥妥当当，要在百忙中挤出时间让小朋友去上汉语补习班，一方面增加了小朋友的负担，另一方面也会导致小朋友在学习的过程中越发功利性，逐渐丧失对中国文化的兴趣。而汉语教育APP可以利用小朋友的碎片时间进行学习，在放松的同时，对汉语的了解增添几分，达到**寓教于乐**的效果。

## 最小完成

* **图像识别**：完成图像识别功能以建立起生活学习与软件学习的联系。

* **语音合成**：实现有声读物功能。


## 本产品主要运用的AI功能如下

* [百度AI-语音技术-语音识别](http://ai.baidu.com/tech/speech/asr)  及   [腾讯AI-语音识别-关键词检索](https://ai.qq.com/product/keywords.shtml)
  * [原型对应页面查看](https://kayuiii.github.io/API_ML_AI/#g=1&p=%E5%85%B3%E9%94%AE%E8%AF%8D%E9%80%A0%E5%8F%A5%EF%BC%88%E8%AF%AD%E9%9F%B3%E8%AF%86%E5%88%ABapi%E5%92%8C%E5%85%B3%E9%94%AE%E8%AF%8D%E6%A3%80%E7%B4%A2api%EF%BC%89)
  
* [百度AI-语音技术-语音合成](http://ai.baidu.com/tech/speech/tts)
  * [原型对应页面查看](https://kayuiii.github.io/API_ML_AI/#g=1&p=%E5%8F%A4%E8%AF%97%E8%AF%8D%E9%98%85%E8%AF%BB%EF%BC%88%E8%AF%AD%E9%9F%B3%E5%90%88%E6%88%90api%EF%BC%89)

* [百度AI-图像识别-通用图像识别](http://ai.baidu.com/tech/imagerecognition/general)
  * [原型对应页面查看](https://kayuiii.github.io/API_ML_AI/#g=1&p=%E8%AF%86%E5%9B%BE%E6%88%90%E5%8A%9F%E9%A1%B5%EF%BC%88%E5%9B%BE%E5%83%8F%E8%AF%86%E5%88%ABapi%EF%BC%89)
  
  
## 产品架构

![基础架构](https://bdn.135editor.com/files/users/126/1261920/201811/xuKnaKcN_CzdS.jpeg)


## API调用展示

* 语音识别API流程示意图

![语音识别](https://bdn.135editor.com/files/users/126/1261920/201811/e3p3CDJL_KO4S.jpg)

* 语音合成API流程示意图（以古诗词为例）

![古诗词](https://bdn.135editor.com/files/users/126/1261920/201811/MAvFrTcc_mtqS.jpg)

* 图像识别API流程示意图

![图像识别](https://bdn.135editor.com/files/users/126/1261920/201811/8z2H9gf6_jTr4.jpg)

* 关键词检索API流程示意图（以关键词造句为例）

![关键词](https://bdn.135editor.com/files/users/126/1261920/201811/uFTrAjP4_wpus.jpg)


## 用户需求

* 显性需求
  * 幼年儿童对于汉语入门、进阶学习、能力提升的需求
  * 家长对于提升儿女汉语能力提升的需求
  
* 隐性需求
  * 一、二线城市，儿童要入学就读知名幼儿园、小学的情况下，需要接受一定的知识考察的需求
  * 小升初压力下，小学生对于巩固语文知识的需求
  


## 目标用户

* 2-12岁的有汉语学习需求的儿童
* 相应年龄段儿童的父母
* 移动设备使用者
* 移动购物与支付用户

## 内容范围

* **汉语学习**

我们将为不同年龄层儿童提供相应的汉语学习，包括汉字字音、书写与阅读，基础词语和成语学习与应用。同时，我们将跳出传统汉语教学的枯燥框架，通过小游戏、图文想象等方式，寓教于乐地让小朋友们更好地学习汉语。

* **古诗词学习**

在古诗词学习模块，小朋友们不仅可以了解并背诵古诗词，增加自身的知识储备，还将通过讲解了解到古诗词中的修辞等手法、作者的生平故事，帮助他们更好地理解古诗词。

* **文言文阅读与学习**

和古诗词学习模块一样，文言文阅读与学习除了让小朋友接触学习文言文之外，也会伴随文章给小朋友讲解文言知识、文章翻译等。

* **名著阅读**

名著阅读模块中，用户可以通过在书城购买已上架的电子版名著，通过电子书的方式进行阅读。在阅读的同时，还嵌入字典模块，遇到不懂的字词可以随时长按查阅字典，帮助小朋友更好地了解和阅读名著，感受名著的魅力。与此同时，还通过**百度API的语音合成功能**，让用户可以通过“听书”的形式进行阅读。

* **回顾与测试系统**

在回顾与测试系统中，用户可以回顾学习过的汉语字词、成语、古诗词、文言文，并可以对已学习的内容进行多次考察。如：按笔画顺序写出某个字、写出三个AABB结构的成语、《桃花源记》表现了作者怎样的情感抱负等。

同时，接入**百度AI的语音识别功能**及**腾讯AI的关键词检索功能**来实现更好的评测效果。


* **图像学习模块**

通过接入**百度API的图像识别功能**，用户在使用照相机拍摄时，可以识别图像内容，进而联想到相应诗句、文言等。如：拍摄物品：琵琶-联想到文言《琵琶行》；拍摄景物：桃花-联想诗句“竹外桃花三两枝，春江水暖鸭先知”等。通过身边事物联想汉语、古诗文能更进一步加深用户对于相关内容的印象，达到更好的学习效果。

## 市场

* 目前市面上**针对幼年儿童**的汉语学习、教育类APP较少且不出众
* 多数汉语教育依存于学校教学、线下补习班、PC端网课，而这些课程都要求幼年儿童在学习时拥有一定强度的注意力，不符合改年龄层的学习习惯

## 运营

* **前期推广**

前期推广部分，我们可以开展“汉字书写”、“汉语知识”等小游戏来让大家认识到汉字书写等重要性。2-12岁的受众父母正巧处于25-40岁的工薪阶层，日常使用汉字多为口头用语，提笔忘字、用词和文书格式不正确等现象时有发生，这类小活动容易引起共鸣。

另外，我们还可以和幼儿园、小学合作开展汉语知识活动，来让更多受众了解到这个软件。


* **后期盈利**

用户进入稳定期后，我们可以在趣味学习的基础上增添花样，例如：与幼儿喜爱的动画形象合作推出学习课程、推出定制的词语/成语包（参考百词斩的定制单词包）、字音教学语音包等付费项目，来进入盈利阶段。
