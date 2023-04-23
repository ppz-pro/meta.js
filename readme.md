# jajcgpdx
``` bash
npm install jajcgpdx
```

# Why jajcgpdx
写程序时，你的第一追求是什么？
+ 功能完整？
+ 运行效率高？
+ 扩展性、可维护性？
+ 小，，咳咳，而美？

我的第一追求是“**写起来得劲**”  
因为我本人水平较低，没去过大厂，没有机会享受 996 福报  
所以参加工作以来，只效力过极小规模的团队，只有偶尔的机会去加加班  
所以有充足的时间，或者说充分的心情，来享受写代码  

写代码多是一件美事啊，除非你享受了 996 福报，也算是鱼和熊掌不能全要  

“得劲”这个词，我老家的方言里也有，但是是在东北上学时才真正学会的  
我很喜欢这个词，说出这俩字时，得用一种放松且略带调皮的语气，才能传达出真正的意思  
“得劲”的含义，我说不明白，它只在我心里有个模糊的感觉  

我也曾认为，拿人钱财，为人打工，应该以“功能完整”为第一追求  
要对得起老板发的工资，或者说要保证自己不被开除  
然后，要把功能做“好”，也就是“运行效率高”  
其次，项目要维护、升级，所以要保持“扩展性、可维护性”  
最后，如果可以的话，要“小”，要“美”  

> 我不喜欢“小而美”这个词，不是因为它本身的意思。而是因为它经常用于形容“非小”（臃肿）且“非美”（丑陋）的东西，就像现在没人会用“卧龙凤雏”去夸奖人。

但是，偶有一次，我认识了 [Ruby](https://www.ruby-lang.org/)  
这个编程语言，在国内并不出名，应用也很少  
我被 Ruby 的理念深深吸引，我觉得这才应该是我的追求  

Ruby 理念的逻辑，大概是这样的：  
听说，欧洲人为了让牛奶更好喝，就让牛上班时，给他们播放音乐，以舒缓牛的心情，真对牛弹琴  
类推一下，程序员得劲了，自然能挤出好奶  
于是“功能完整”、“运行效率高”、“扩展性、可维护性”、“小而美”都可以是“得劲”的产物  
程序员得劲了，他更容易也更愿意去追求其他的东西  
我不知道别人怎样，我只知道，谁让我 996，我就在谁的代码里下毒  

那么，，，，，Why jajcgpdx？  
因为 jajcgpdx 能让我得劲，我自己  
（对不起我没有理由让你用 jajcgpdx，我不推荐你用）  
jajcgpdx 首先是一个工具库，但是和 [locash](https://lodash.com/) 或 [underscore](https://underscorejs.org/) 这类“函数式”工具库不同的是，它采用了一种比“面向对象”更容易使代码混乱的方式——**元编程**来实现  
他不是给你一些东西，让你去用，而是可能去修改你现有的东西  
比如，你想要一个“最大值”，在 lodash：
``` javascript
import _ from 'lodash'

const max = _.max([1, 2, 3, 4, 5])
```
而在 jajcgpdx：
``` javascript
const max = [1, 2, 3, 4, 5].max()
```

直接去修改现有的东西，很危险，这也是我起了个 jajcgpdx 这样的名字的原因  
这个名字是[随机生成](https://github.com/ppz-pro/meta.js/blob/727957bac8a6f0b1caddc7343de3f30cb7f69fca/random-string.test.coffee#L49)的，不带有任何含义，这是一种极差的命名方式  
就像元编程，在一些角度上说，也是一种极差的编程方式  
我真心不推荐你使用 jajcgpdx，除非...

另外，为了方便我自己，我还在 @ppzp/meta 的名字下，发布了同样的库：
``` bash
npm install @ppzp/meta
```
