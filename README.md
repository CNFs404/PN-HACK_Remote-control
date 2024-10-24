![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)
# 😃项目简介

本项目是一款由易语言制作的远程控制程序，功能齐全，并开源于2024年10月23日。

## 界面展示
![image](https://github.com/user-attachments/assets/c5c76d59-77e8-4e2b-8aec-e0f64e7272d8)
![image](https://github.com/user-attachments/assets/6b5fee8e-7e5a-49e4-ab33-1bc485933eaf)
![image](https://github.com/user-attachments/assets/1936ee52-f4b0-472f-b097-1e65c9ca4738)

## 项目背景

随着网络技术的发展，远程控制技术在各个领域得到了广泛应用。远程控制技术可以帮助用户在不同地点管理和控制计算机，提高了工作效率和便利性。本项目旨在提供一种简单、易用的远程控制解决方案，满足用户在不同场景下的远程控制需求。

## 功能分支

- **slave.e**：被控端，负责接收管理端的指令并执行相应的操作。
- **master.e**：管理端，用于发送指令和控制被控端。
- **中继端2.0.e**：服务端，作为中继节点，负责连接管理端和被控端，确保远程控制过程的稳定性和安全性。

## 🌐模块引用
  - **EXUI支持库最新版即可-|
  - **精易模块10.3v and 精易模块v3.0
  - **VMP加密模块
  - **超级模块8.0正式版

## 项目优势

- **易语言开发**：采用易语言进行开发，降低了项目的开发门槛，使得更多用户能够参与和使用。
- **功能齐全**：提供了丰富的远程控制功能，满足用户在不同场景下的需求。
- **开源共享**：项目开源，用户可以自由使用、修改和分发，促进了技术的交流和进步。

我们期待通过本项目的推广和应用，为远程控制技术的发展贡献一份力量。

## 目前问题
公网环境中由于官方组件过于太旧,导致上传下载仅限于5KB,这使得视频监控会无法正常使用,如果你懂得HTTP传输或者Socke传输欢迎更新修改

### ------------------------------------------------------------使用方法------------------------------------------------------------
- **0.编译中继端,并运行在公网服务器或本地测试机
- **1.更改<slave被控端>和<master主控端>代码中"常用变量"中的"服务器IP":为你指定中继端所在的IP",修改后即可编译成EXE文件
- **2.在虚拟机或肉鸡上运行生成的slave.exe
- **3.master主控端将会收到上线信息,尽情的玩弄吧
