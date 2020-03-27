# 软件测试基础

**Ling Gao 的软件测试基础学习笔记** :stuck_out_tongue_closed_eyes:

[![Ling Gao](https://img.shields.io/badge/Author-Ling_Gao-blue)](https://answers.microsoft.com/zh-hans/profile/4e1113c0-eb29-4e90-9782-f1931bae8489)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-blue.svg)](https://en.wikipedia.org/wiki/Markdown) 
[![CC0-1.0 license](https://img.shields.io/badge/License-Creative_Commons_Zero-blue.svg)](https://github.com/Lingggao/Software-Testing-Basics/blob/master/LICENSE)

> 作者 - **Ling Gao (高楷修)**  
> 师承 - **XiaoPeng Li (李晓鹏) | HongXing Cao (曹红杏)**  
> 学校 - **HNIST (湖南理工学院)**  
> 许可证 - **Creative Commons Zero v1.0 Universal**

## 目录

### 第一章

- [**§ 1.1 - 软件测试发展史**](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_1_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2.md#-11---%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2)
	- [一、软件测试行业发展历程](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_1_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2.md#%E4%B8%80%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E8%A1%8C%E4%B8%9A%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B)
	- [二、中国软件测试发展历程（截止至 2013 年）](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_1_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2.md#%E4%BA%8C%E4%B8%AD%E5%9B%BD%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8E%86%E7%A8%8B%E6%88%AA%E6%AD%A2%E8%87%B3-2013-%E5%B9%B4)
	- [三、软件测试人才](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_1_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2.md#%E4%B8%89%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E4%BA%BA%E6%89%8D)
	- [四、软件测试晋升路线](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_1_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%8F%91%E5%B1%95%E5%8F%B2.md#%E5%9B%9B%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E6%99%8B%E5%8D%87%E8%B7%AF%E7%BA%BF)
- [**§ 1.2 - 软件测试的定义、目的、对象与分类**](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_2_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E3%80%81%E7%9B%AE%E7%9A%84%E3%80%81%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB.md#-12---%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E7%9B%AE%E7%9A%84%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB)
	- [一、定义](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_2_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E3%80%81%E7%9B%AE%E7%9A%84%E3%80%81%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB.md#%E4%B8%80%E5%AE%9A%E4%B9%89)
	- [二、目的](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_2_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E3%80%81%E7%9B%AE%E7%9A%84%E3%80%81%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB.md#%E4%BA%8C%E7%9B%AE%E7%9A%84)
	- [三、对象](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_2_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E3%80%81%E7%9B%AE%E7%9A%84%E3%80%81%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB.md#%E4%B8%89%E5%AF%B9%E8%B1%A1)
	- [四、分类](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_2_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%AE%9A%E4%B9%89%E3%80%81%E7%9B%AE%E7%9A%84%E3%80%81%E5%AF%B9%E8%B1%A1%E4%B8%8E%E5%88%86%E7%B1%BB.md#%E5%9B%9B%E5%88%86%E7%B1%BB)
- [**§ 1.3 - 软件测试环境**](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_3_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83.md#-13---%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83)
	- [一、软件测试流程](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_3_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83.md#%E4%B8%80%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E6%B5%81%E7%A8%8B)
	- [二、测试环境概述](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_3_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83.md#%E4%BA%8C%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83%E6%A6%82%E8%BF%B0)
	- [三、测试环境搭建原则](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_3_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83.md#%E4%B8%89%E6%B5%8B%E8%AF%95%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%E5%8E%9F%E5%88%99)
- [**§ 1.4 - 软件测试的时间、信息流程与周期性**](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_4_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E3%80%81%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7.md#-14---%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7)
	- [一、软件生命周期](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_4_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E3%80%81%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7.md#%E4%B8%80%E8%BD%AF%E4%BB%B6%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F)
	- [二、软件测试时间](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_4_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E3%80%81%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7.md#%E4%BA%8C%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E6%97%B6%E9%97%B4)
	- [三、测试信息流程](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_4_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E3%80%81%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7.md#%E4%B8%89%E6%B5%8B%E8%AF%95%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B)
	- [四、软件测试周期性](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_4_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E6%97%B6%E9%97%B4%E3%80%81%E4%BF%A1%E6%81%AF%E6%B5%81%E7%A8%8B%E4%B8%8E%E5%91%A8%E6%9C%9F%E6%80%A7.md#%E5%9B%9B%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%91%A8%E6%9C%9F%E6%80%A7)
- [**§ 1.5 - 软件测试的停止依据**](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_5_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%81%9C%E6%AD%A2%E4%BE%9D%E6%8D%AE.md#-15---%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%81%9C%E6%AD%A2%E4%BE%9D%E6%8D%AE)
	- [一、推荐依据](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_5_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%81%9C%E6%AD%A2%E4%BE%9D%E6%8D%AE.md#%E4%B8%80%E6%8E%A8%E8%8D%90%E4%BE%9D%E6%8D%AE)
	- [二、推荐标准](https://github.com/Lingggao/Software-Testing-Basics/blob/master/%E7%AC%AC%E4%B8%80%E7%AB%A0/1_5_%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E7%9A%84%E5%81%9C%E6%AD%A2%E4%BE%9D%E6%8D%AE.md#%E4%BA%8C%E6%8E%A8%E8%8D%90%E6%A0%87%E5%87%86)
- [**§ 1.6 - [整理中]**](https://github.com/Lingggao/Software-Testing-Basics)

---
[**回到顶部**](https://github.com/Lingggao/Software-Testing-Basics#%E8%BD%AF%E4%BB%B6%E6%B5%8B%E8%AF%95%E5%9F%BA%E7%A1%80)
