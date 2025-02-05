[![Version](https://img.shields.io/badge/Version-23.6-cornflowerblue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/shaucky/Petdoctor_2023/blob/main/LICENSE)
[![AIR Version](https://img.shields.io/badge/AIR-50.2-darkred.svg)](https://airsdk.harman.com)

# Petdoctor 2023

<b><i>Petdoctor 2023是一款基于AIR开发的《赛尔号》页游对战动画播放器</i></b>。

用户可以使用Petdoctor 2023预览《赛尔号》页游Flash端的对战动画。Petdoctor 2023模拟了游戏内实际的对战效果，精确定位了双方精灵，支持无缝衔接雷伊和米卡的特殊技能、异度裁决·至序圣华的第五技能、瀚宇星皇的星皇之怒、混元天尊和机械系精灵王的变身。Petdoctor 2023使用的是AIR原生的Flash内容渲染机制，无跳帧，完整播放动画内容。性能主要受CPU影响，对动画的流畅程度不做担保。

----------

## 如何使用

Petdoctor 2023可以在除iOS以外AIR支持的操作系统中运行<i>（即Windows、MacOS、Linux和Android）</i>。Petdoctor 2023只有一个主窗口。启动Petdoctor 2023后，可以看到类似《赛尔号》战斗界面的界面。

默认情况下，Petdoctor 2023会加载《赛尔号》页游（https://seer.61.com/ ）序号1的精灵动画（布布种子）。

在界面的下方，有一排共计4个按钮。单击这些按钮可以播放我方（左侧）精灵动画的相应动作，包括物理攻击、特殊攻击、属性攻击、登场动画。在原本的技能动画触发节点，会直接播放对方（右侧）精灵动画的受击动作。通过这些功能，可以起到预览游戏内的对战动画，或者本地的对战动画的作用。

在界面的右下方，有一组共计4个按钮，分别用于
* 场景设置
* 关于Petdoctor 2023
* 精灵设置
* 退出Petdoctor 2023

主要介绍精灵设置：

1. 打开精灵设置面板，其中可以输入想要加载的双方（两侧）精灵动画的序号。
2. 其中，对于我方精灵动画，现版本允许加载本地SWF文件，只要符合《赛尔号》精灵动画规格即可。浏览至对应文件后，勾选“使用本地文件”选框即可。
3. 如果动画本身存在扩展动作，还需要勾选相应的选框，例如“星皇之怒（衔接）”。
4. 完成上述操作后，单击“修改”按钮，Petdoctor 2023会重新加载新指定的精灵动画，并生效相关勾选项。

看明白了吗？可以尝试一下！希望Petdoctor 2023对你有帮助！

----------
 
Petdoctor具有多年的历史，最早可以追溯到2017年，晓痴（那时候还叫“小痴”）尝试开发的<b>赛尔号对战动画播放器</b>。依稀记得，那时候晓痴刚开始接触ActionScript，开发的对战动画播放器连显示对象列表都把握不好，在一些操作之后甚至可能有UI被移除。开发Petdoctor让晓痴逐渐地熟悉了ActionScript、Flash以及AIR。也为晓痴奠定了深厚的OOP基础。
 
<b>Petdoctor 2023现已停止支持</b>。感谢各位用户和同好在过去一年的支持。

由于晓痴最近降低了对《赛尔号》页游的关注，同时2023年也已经结束，决定停止支持Petdoctor 2023。

现已将Petdoctor 2023可通过编译的源文件（含FLA文档和XML描述文件）上传至Github储存库，<b>可以在任何支持ActionScript 3.0的Flash Professional或Animate中通过编译。需要配置AIR SDK from Harman 50.2或更高版本</b>（https://airsdk.harman.com/ ）。

存储库的许可协议已更改为MIT协议，希望各位同好在二次修改或分发Petdoctor的部分或全部时，可以保留晓痴的著名。感谢。
