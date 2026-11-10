# 星尾狐 · 桌面陪伴助手

一只悬浮在 Windows 桌面的 3D 狐狸，陪你工作，在工作间隙通过轻量互动放松心情。

## 功能

- 透明、置顶的桌面窗口，可拖动位置。
- 喂食、玩耍、休息和改名；状态自动保存。
- Lv.3 根据互动偏好进入花野、星光或月梦路线；Lv.6 再次成长。进化目前改变称号和装饰，不改变狐狸模型。
- 3D 模型包含待机及奔跑动画。

## 运行与打包

需要 Node.js 和 npm，在项目目录执行：

```sh
npm install
npm start
npm run build
```

打包后的 Windows 程序位于 `release/FoxCompanion-win32-x64/`，分发时需保留整个目录。首次安装 Electron 需要联网。构建产物和依赖未提交到仓库。

## 使用

拖动宠物周围空白区域移动窗口，底部按钮用于互动；打开“养成”面板可查看进化路线、改名、重置或退出。宠物进度保存在 Electron 用户数据目录。

## 素材授权

狐狸模型来自 [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/Fox)：PixelMannen（模型，CC0）、tomkranis（骨骼和动画，CC BY 4.0）、AsoboStudio 和 scurest（glTF 转换，CC BY 4.0）。详见 [素材授权](素材授权.txt)。本项目不包含 dsh-pet 的图像素材。
