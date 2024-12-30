# GenshinWishSimulator_CXX
原神限定卡池祈愿模拟

## 关于程序
目前程序还是不完美，存在一些问题，例如：
- 程序在抽取四星时，如果获得了非当期UP四星时，需要判定出武器还是角色，此外，如果连续出四星角色，那么下一发四星出武器概率应当提高
- 程序没有实现原神5.0版本新增的**捕获明光**机制
- 程序目前只可以模拟原神的限定角色卡池，我希望可以加入武器池，以及崩坏：星穹铁道和绝区零的卡池
- 每次抽卡前需要写入距离上次出金、出紫的抽数，我希望可以写通过Json文件来，记录这两个值，并在抽卡后进行更新
- 可以通过输入原石数量，将原石数量转化为抽数，方便部分使用者更方便的模拟抽卡
- 我希望未来抽卡数据可以导出为Excel表格或其他数据格式文件，方便进行数据可视化（我的pyechart啊）
- 程序目前没有GUI页面，命令行黑乎乎的，就算有GUI，我也希望这个GUI可以好看些
- 程序可以写一个接口实现，例如：`GenshinWishSimulator.exe -wish 10`可以直接进行十连抽取，并将结果写入数据文件；`GenshinWishSimulator.exe -setPrimogem 100000`设置原石数量为`100000`等等

## 另外
不要给本项目提Issues，PR。这只是一个一时兴起做的项目，目前并不打算长期更新，提了会被晾在那里。不过，欢迎你下载源代码自己修改和发布（需要遵循开源协议）。预计2025年的夏天，我会回来继续更新这个项目。


## 声明（第三方库 与 相关参考）
### JSON for Modern C++
Niels Lohmann  
https://github.com/nlohmann/json

### Random for modern C++ 
effolkronium (Illia Polishchuk)   
https://github.com/effolkronium/random   

### 概率数据参考：
https://www.bilibili.com/read/cv12616453/  
*作者：OneBST* >> https://space.bilibili.com/6165300
