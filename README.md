﻿## 前言
实在是有点迟到，最近才把layer托管到github，目的是收集更优秀的代码，以让其“易用和实用性”具备更强大的技术支撑。因此我们强烈呼吁有缘人加入进来，共同完善这位最懂你的精灵。

## 愿景
致力于打造国内最盛行的弹层组件，为web开发提供强劲动力。


## 简要
layer遵循于LGPL开源协议，她是一枚可以让你想到即可做到的新生代web弹窗/层js组件。layer侧重于用户灵活的自定义，为不同人的使用习惯提供全方位设计，您的页面会因此拥有更丰富、友好的操作体验，而您只需在调用时简单地配置相关参数，即可轻松实现各类交互。

与同类弹出层组件相比，layer的优势明显，她尽可能地在以更少的代码展现出更强健的功能。layer格外注重性能的提升、易用和实用性，正因如此，越来越多的开发者将媚眼投上了小小的layer。当你问及她的兼容时，layer必须告诉你，她兼容了一切浏览器，包括古老的ie6。layer公开了如此多的接口，这使得您可以DIY太多您需要的风格，尤其是页面层模式，意味着必要时您可以完全抛弃layer的现有皮肤，并用你的思维去勾勒她的衣着。而问题在于，我必须中止“王婆卖瓜”的陈述。因为一切的不足或友好，都需要您在使用过程中去发现。

## 现状
从两年前初出茅庐，到后来成为小众组件，再发展到今天，已为数以万计的人所熟知。
据不完全统计，截至到2014年5月13号，layer已服务于15万多家web平台。
其中包括：
* [中国联通](http://app.10010.com/)
* [蚂蚁短租](http://www.mayi.com/)
* [phpyun](http://www.phpyun.com/)
* [卡牌网](http://www.kapai.com/)
* [八圆包](http://www.bayuanbao.com/)


事实上我们无法获取到更多案例，所以如果您有大型项目也在使用layer，您可以联系作者，以便在layer官网展现，也为您的品牌推广尽一些绵薄之力。

## 日志
【1.8.4更新日志】
* 新增浏览器窗口尺寸改变时的自适应定位
* 新增属性shift，用于配置动画弹出（需要注意的是，之前的layer.shift()方法将在layer1.9遗弃，用shift属性取代）
* 新增方法layer.title(name, index); 用于动态改变层的标题。
* 修改弹出层默认初始坐标为垂直左右居中。
* 开放多个tips，可通过配置tips: {more: true}开启。
* 进一步完善tips的智能定位。
* 放弃layer.ready方法，用jQuery的ready取代。
* 进一步优化内部代码

== 拓展模块 ==
* layer.prompt支持给表单传入默认值，如layer.prompt({val:'默认'}); 新增yes回调函数第二个参数为索引、第三个参数为表单元素。
* 相册层新增tab回调函数，用于切换图片时进行相关操作
* 相册层内部代码优化。


## 备注
[官网](http://sentsin.com/jquery/layer/)、[更新日志](https://github.com/sentsin/layer/blob/master/Update%20Notes.txt)、[Say交流](http://say.sentsin.com/home-48.html)、[商业支持](http://url.cn/RAejZY)