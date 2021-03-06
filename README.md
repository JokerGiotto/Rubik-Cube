# DirectX实现的3D魔方游戏

![](https://github.com/MKXJun/Rubik-Cube/blob/master/replay.gif)

**教程链接：[DirectX11--实现一个3D魔方](https://www.cnblogs.com/X-Jun/p/10230580.html)**

## Direct3D 11.x实现版本 V1.1

语言：C++11/14</br>
开发环境：Visual Studio 2017</br>
依赖项：无</br>
配置支持：Debug/Release支持</br>
平台支持：x86/x64</br>
最低Windows SDK版本要求：8.1</br>
最低Visual Studio版本要求：2015</br>
最低系统要求：Windows 7

**提醒：**</br>
-不支持Direct3D 11.1的系统将无法看到文本输出，但不影响游戏体验。</br>
-现在即便是移除Resource文件夹，程序也会自己生成一样的纹理。

## Direct3D 9实现版本 V1.0

**注意：由于本人的Win10系统已经无法打开DirectX 9的游戏，故不再维护**

语言：C++11</br>
开发环境：Visual Studio 2017</br>
依赖项：DirectX SDK</br>
配置支持: Debug/Release支持</br>
平台支持: x86/x64</br>
最低Windows SDK版本要求：8.1</br>
最低Visual Studio版本要求：2015</br>
最低系统要求：Windows 7

## 使用说明

打开魔方.exe，魔方开局将会自动打乱。

打乱结束后，玩家可以用键盘或者鼠标进行操作。当魔方发生实质性转动时，计时器将开始计时。当完成魔方后，游戏会弹出窗口告诉你完成用时。

如果你使用了一键还原，将不计入成绩。

## 键鼠操作说明

以下为键位操作(两个版本都不一定完全支持)

|键位    |对应公式|描述|键位   |对应公式|描述|
|--------|----|------------------------|--------|----|------------------------|
| Up     | x  | 整个魔方按x轴顺时针旋转|I       | R  | 右面两层按x轴顺时针旋转|
| Down   | x' | 整个魔方按x轴逆时针旋转|K       | R' | 右面两层按x轴逆时针旋转|
| Left   | y  | 整个魔方按y轴顺时针旋转|J       | U  | 顶面两层按y轴顺时针旋转|
| Right  | y' | 整个魔方按y轴逆时针旋转|L       | U' | 顶面两层按y轴逆时针旋转|
| Pg Up  | z' | 整个魔方按z轴逆时针旋转|U       | F' | 正面两层按z轴逆时针旋转|
| Pg Down| z  | 整个魔方按z轴顺时针旋转|O       | F  | 正面两层按z轴顺时针旋转|
|--------|----|------------------------|--------|----|------------------------|
|LCtrl+I | r  | 右面两层按x轴顺时针旋转|T       | M  | 右面两层按x轴顺时针旋转|
|LCtrl+K | r' | 右面两层按x轴逆时针旋转|G       | M' | 右面两层按x轴逆时针旋转|
|LCtrl+J | u  | 顶面两层按y轴顺时针旋转|F       | E  | 顶面两层按y轴顺时针旋转|
|LCtrl+L | u' | 顶面两层按y轴逆时针旋转|H       | E' | 顶面两层按y轴逆时针旋转|
|LCtrl+U | f' | 正面两层按z轴逆时针旋转|R       | S' | 正面两层按z轴逆时针旋转|
|LCtrl+O | f  | 正面两层按z轴顺时针旋转|Y       | S  | 正面两层按z轴顺时针旋转|
|--------|----|------------------------|--------|----|------------------------|
|LCtrl+W | l' | 左面两层按x轴逆时针旋转|W       | L' | 右面两层按x轴顺时针旋转|
|LCtrl+S | l  | 左面两层按x轴顺时针旋转|S       | L  | 右面两层按x轴逆时针旋转|
|LCtrl+A | d' | 底面两层按y轴逆时针旋转|A       | D' | 顶面两层按y轴顺时针旋转|
|LCtrl+D | d  | 底面两层按y轴顺时针旋转|D       | D  | 顶面两层按y轴逆时针旋转|
|LCtrl+Q | b  | 背面两层按z轴顺时针旋转|Q       | B  | 正面两层按z轴逆时针旋转|
|LCtrl+E | b' | 背面两层按z轴逆时针旋转|E       | B' | 正面两层按z轴顺时针旋转|
|--------|----|------------------------|--------|----|------------------------|
|F9      |    | 拾取模式(仅DirectX 9)  |F10     |    | 一键还原               |
|F11     |    | 重置游戏               |F12     |    | 关于作者(排行榜仅DX9)  |
|LCtrl+Z |    | 撤销操作               |        |    |                        |


鼠标左键拖动魔方块旋转一层魔方</br>
鼠标左键拖动空白区域旋转整个魔方</br>






















