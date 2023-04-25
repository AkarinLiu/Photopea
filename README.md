# PhotoPea
![Photopea](icon.ico)
## 简介
Photopea是一个基于在线的图像编辑器，本客户端专为Photopea而设计。
## 获取
你可以到GItHub Actions标签获取最新编译的Photopea
## 构建
执行以下命令：
### Windows
```
npx nativefier -n Photopea -p win32 --arch x64 --icon icon.ico https://www.photopea.com build
```
### macOS
```
npx nativefier -n Photopea -p mac --arch x64 --icon icon.ico https://www.photopea.com build
 ```
 ### Linux
 ```
 npx nativefier -n Photopea -p linux --arch x64 --icon icon.ico https://www.photopea.com build
 ```
## 已知问题
- 启动时一直处于白窗口
- 构建可能会报错