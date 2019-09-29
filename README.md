
<div align="center">
<img width="100" height="100" src="MajiaTools/logo.png" alt="logo.png"/>
</p>
</div>

## 马甲小助手是什么?
马甲小助手是一个为开发者提供方便制作和分析马甲包的工具.目前处于测试和完善阶段,免费开放给广大开发者使用

## TODO LIST(部分功能会在后面逐步加上)
- [x] 修改类名
- [x] 修改方法名
- [x] 修改变量
- [x] 修改文件夹
- [x] 支持xib、storyborad
- [x] 黑名单(文件夹,类名,方法名,变量)
- [ ] 添加前缀(文件夹,类名,方法名,变量)
- [ ] 修改资源
- [ ] 添加混淆资源(辣鸡代码)
- [ ] 加密字符串
- [ ] 清除注释,修改文件注释(虽然注释并不参与编译)
- [ ] 高可用性命名
- [ ] Swift兼容

## 对比市面上的常见的混淆工具
* 市面上目前的混淆工具
    * 大部分基于Python的查找替换,效率低而且出错率高,复杂一点的项目完全没法用
    * 需要过滤绝大部分的第三方库,混淆不彻底
    * 没有考虑系统关键字和大部分系统方法,容易出错
    * 没有图形化界面或用户体验太差
* 马甲小助手
    * 抛弃原有市面上的常规做法,使用高效匹配,效率高出错率低,兼容各种大型工程
    * 无需过滤第三方库
    * 自动扫描工程依赖的系统库,过滤更加彻底
    * 专门为MacOS优化的图形界面

## 目前主要功能
* 快速便捷,操作简单
  * 提供项目的.app文件
  * 提供项目的根目录路径
* 自动忽略系统方法.系统变量,pods文件夹
* 混淆率更高,混淆后编译bug更少
  * 自动分析可混淆的符号(第三方库不在pods文件夹时也参与混淆)
  * 修改方法名时支持换行方法,嵌套方法等修改
  * 精准替换(效果类似xcode的refactor-rename)
* 支持多种模式,快速模式和自定义模式

## 使用方法
### 拖入.app文件和工程跟目录
![avatar](https://raw.githubusercontent.com/MajiaTools/MajiaTools/master/MajiaTools/step.png)

### 自定义配置
![avatar](https://raw.githubusercontent.com/MajiaTools/MajiaTools/master/MajiaTools/step1.png)


