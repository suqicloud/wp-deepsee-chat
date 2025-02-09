<img src="https://github.com/suqicloud/wp-ai-chat/blob/main/ic_logo.png" width="60">

# 小半WordPress ai助手  

[![License](https://img.shields.io/badge/license-GPL-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-2.5-green.svg)](https://github.com/suqicloud/wp-ai-chat/releases/tag/1.8)
[![WordPress](https://img.shields.io/badge/WordPress-6.7-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-8.0-orange.svg)](https://www.php.net/)



## 📌 项目简介

全开源免费 - WordPress ai助手插件，可实现：ai对话、ai文章生成、ai文章总结、ai文章翻译、文章内容朗读、ai回复内容朗读。  

2.0和之前采用非流式实现的ai对话聊天，如果ai返回的内容过多，可能会卡，无法及时显示出来。   
2.2开始采用流式输出ai对话聊天，需要网站开启REST API服务，有的用户优化wp的时候可能会关掉REST API。  

## 🚀 功能特性

1.支持对接deepseek  
2.支持选择DeepSeek-V3、DeepSeek-R1模型  
3.支持对接豆包ai  
4.可以自定义豆包ai文本类型的模型  
5.支持对接通义千问  
6.支持常用的通义千问模型  
7.支持通义千问的图片生成  
8.系统会用一个单独的数据表保存对话记录的第一句  
9.用户可以删掉自己的历史对话记录   
10.后台可以删掉用户的对话记录  
11.可以通过关键词生成文章  
12.可以通过ai接口对文章进行总结  
13.前台显示一个ai助手入口  
14.只允许登录用户使用  
15.支持Markdown格式  
16.DeepSeek余额信息  
17.通过ai接口对文章进行翻译  
18.支持对接腾讯云、百度云TTS服务实现朗读文章内容  
19.可以实现朗读ai回复的文字内容  
20.可以自定义提示词


## 📥 安装

1. 下载最新版本文件。
2. 进入WordPress插件后台
3. 上传本地文件包安装

或者直接上传到服务器的网站插件目录/wp-content/plugins也行，记得设置权限。  

开发基础：WordPress 6.7.1  
php版本：php 8.0  

## 🛠️ 使用方法

插件启用会自动创建一个前台对话页面。如果没有自动创建，就自己手动加短代码：  [deepseek_chat]  

文章翻译的接口要单独设置，因为这本来是我另外一个插件的，我合并过来了，不想折腾，就直接用了，  

如果插件不用了，自己到数据库去删掉这个数据表：deepseek_chat_logs  

教程：https://www.wujiit.com/wpaidocs

主题页面需要支持全宽或者全屏模式，不然很狭窄。如果不支持就自己查看你主题的样式，通过代码实现deepseek助手页面全屏显示。  

这款插件最早是为了测试deepseek自己写代码的能力，有一部分是deepseek自己写的代码(ai对话对接deepseek和最早版本的文章生成)，后面又合并了其他插件，所以代码里面的函数名称啥的看起来很乱，但是都写了注释。  



![WordPressai.png](https://github.com/suqicloud/wp-ai-chat/blob/main/2025020801.jpg)
