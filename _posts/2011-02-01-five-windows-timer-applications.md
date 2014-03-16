---
title: 5 个 Windows 计时器软件
author: oumu
layout: post
permalink: /five-windows-timer-applications.html
views:
  - 3474
categories:
  - Miscellaneous
  - 软件
tags:
  - productivity
  - windows
---
&#160;&#160;&#160;&#160;&#160;&#160;&#160; 最近一直在优化自己的时间管理方案，之前使用chrome webstore中的**[Clock][1]**作为计时器。上周Lifehacker的Hive Five主题是“Windows计时器软件”：[http://lifehacker.com/5747056/five-best-windows-timer-applications][2]，将5个计时器都简单试用了一下，记录如下：

<!--more-->

&#160;

<a href="http://img.ioumu.com/aaf2d1cc4409_10CA5/Timer_by_MeisterDesZirkuss.png" target="_blank"><img style="display: inline; float: right" title="Timer_by_MeisterDesZirkuss" alt="Timer_by_MeisterDesZirkuss" align="right" src="http://img.ioumu.com/aaf2d1cc4409_10CA5/Timer_by_MeisterDesZirkuss_thumb.png" width="240" height="240" /></a>

**Orzeszek Timer**

&#160;&#160;&#160; portable，内存占用约17MB；时间设置方式独特、多样；只支持倒计时；可循环倒计时；支持命令行参数调用。

**Focus booster**

&#160;&#160;&#160; 基于Adobe air，内存占用约37MB；时间输入不方便；只能倒计时，倒计时之间可设置最小5分钟的间隔。

**CookTimer**

&#160;&#160;&#160; portable，内存占用约2MB；只能倒计时，4个预设时间（3、5、10、15分钟）或自定义时间；选项只有“自动重新开始计时”和“响铃不止”

**Snaptimer**

&#160;&#160;&#160; portable，内存占用约3MB；   
&#160;&#160;&#160; 时间设置单位为分钟，支持倒计时或秒表，可自动开始和重新开始计时，通过左键单击时间面板可在“开始”和“暂停”间切换，双击为时间重置；   
&#160;&#160;&#160; 提示方式多样，弹窗、托盘气泡、声音或者运行程序；   
&#160;&#160;&#160; 界面可置顶，可以最小化至托盘，托盘图标可显示当前计时器的状态（运行、暂停或结束），任务栏、托盘图标提示和托盘右击菜单都可以显示当前时间；   
&#160;&#160;&#160; 支持命令行参数调用。

**Cool Timer**

&#160;&#160;&#160; 需安装，内存占用约3MB；   
&#160;&#160;&#160; 时间设置分为时、分、秒，支持倒计时、闹钟和秒表，可自动重新开始计时；   
&#160;&#160;&#160; 提示方式为声音或弹窗；   
&#160;&#160;&#160; 界面可置顶，可最小化至托盘，托盘图标提示可显示当前时间；

作为美UI控，**Focus booster**是我第一个尝试对象，不过时间设置不方便，直接放弃。**Orzeszek**时间设置方式很好玩，不过功能相对较少。**CookTimer**功能太简单，不能满足我的需求。 **Cool Timer**功能不错，不过界面太丑，尤其是提示时间到的窗口……官网上说可以自定义界面，没兴趣深究。**Snaptimer**体积小巧、界面质朴、功能强大，尤其是由于支持命令行参数启动，因此Snaptimer可以和**Launchy**结合，快速启动倒计时。

最终选用**Snaptimer**。

Launchy + Snaptimer 设置方法：

&#160;&#160;&#160; “Launchy选项” → “插件” → “Runner” → “+” →

<table border="1" cellspacing="0" cellpadding="2" width="457">
  <tr>
    <td valign="top" width="78">
      Name
    </td>
    
    <td valign="top" width="377">
      timer
    </td>
  </tr>
  
  <tr>
    <td valign="top" width="78">
      Program
    </td>
    
    <td valign="top" width="377">
      C:\Windows\System32\cmd.exe
    </td>
  </tr>
  
  <tr>
    <td valign="top" width="78">
      Arguments
    </td>
    
    <td valign="top" width="377">
      D:\Software\windows\portable\SnapTimer\SnapTimer.exe $$
    </td>
  </tr>
</table>

注：请自行调整目录位置；“$$”指代用户键入的内容；Orzeszek Timer也可做类似设置。

&#160;&#160;&#160; 需要计时的时候，快捷键（alt+spacebar）打开launchy → Tab → 输入数字 → Enter即可。推荐将Snaptimer设为自动开始计时。

<strike>后记：Lifehacker的Hive Five投票显示Focus Booster的支持率最高……于是以后看Hive Five不能片面的根据投票结果选择软件。</strike>

&#160;

2011-02-07： 我对**Focus timer**的功能理解有误，参见此文：[The Pomodoro Technique Fights Deadline Anxiety with a Timer][3]，chrome也有基于“西红柿技巧”的扩展：[ChromoDoro &#8211; Google Chrome extension gallery][4]。   
&#160;&#160;&#160; 另外这篇文章：[Use a Timer as a Productivity Booster and Sanity Minder][5] 提供了一些关于计时器选择和使用的建议，也许我应该选择一个好的实物计时器了。

 [1]: https://chrome.google.com/webstore/detail/hoihofapbdnldlhecnhefifbcddgdkhm "Clock"
 [2]: http://lifehacker.com/5747056/five-best-windows-timer-applications "Five Best Windows Timer Applications - Lifehacker"
 [3]: http://lifehacker.com/5377906/the-pomodoro-technique-fights-deadline-anxiety-with-a-timer
 [4]: https://chrome.google.com/extensions/detail/edhkjecdcakijjmlelnjjiohjmlaikhb
 [5]: http://lifehacker.com/5638746/use-a-timer-as-a-productivity-booster-and-sanity-minder