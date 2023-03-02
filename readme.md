## WarOfGods
War of gods(诸神之战）
缘由：
> 1. 学习 Rust, 搞一个游戏练练手，升职加薪没烦恼。ps:~~为了能合理的在家打游戏~~
> 2. 体验开外挂的纯正快感体验（游戏提供Python接口，写锁头锁血爆头，飞天遁地，在允许的范围内随意操作，只要你的代码牛逼，你就可以称霸服务器。）

## 游戏概念
本游戏是一款基于射击和生存的多人在线游戏。玩家需要在一片广阔的战场上与其他玩家展开竞争，最后生存下来成为唯一的胜者。游戏采用第一人称视角，玩家可以自由移动和探索游戏世界，并通过收集武器、装备和资源来提高自己的生存能力。游戏的核心玩法是“战术射击”和“战术生存”。

### 玩法
#### 地图设计
游戏地图采用随机生成的方式，每次游戏都会生成一个全新的地图。地图分为多个区域，包括城市、森林、山脉、海滩等。每个区域都有自己的地形、建筑和资源分布。

#### 游戏模式
游戏分为两个阶段：**收集阶段**和**生存阶段**。

> 收集阶段：在游戏开始时，所有玩家都被放置在地图的某个随机位置。玩家需要在地图上寻找武器、装备和资源，以提高自己的生存能力。在这个阶段，地图的边界会不断缩小，玩家需要不断向安全区域移动，以免被边界淘汰。

> 生存阶段：当地图缩小到一定程度后，所有玩家将被迫进入一起战斗。在这个阶段，玩家需要利用自己收集到的装备和资源，与其他玩家展开激烈的战斗。最后，最后存活下来的玩家将成为游戏的胜者。

#### 角色设定
玩家可以选择不同的角色进行游戏，每个角色都有自己的**属性**和**特殊技能**。

> 属性：包括生命值、体力、攻击力、防御力等。

> 特殊技能：包括隐身、跳跃、冲刺等。

#### 武器装备
游戏中有多种不同类型的武器和装备，包括*手枪*、*步枪*、*狙击枪*、*防弹衣*、*头盔*等。每种武器和装备都有自己的*属性*和*特点*，玩家需要根据自己的战术和游戏进程来选择合适的武器和装备。


#### 关卡设计
游戏中的关卡设计主要分为**收集阶段**和**生存阶段**。

#### 收集阶段
在收集阶段中，游戏地图会根据随机算法生成一片广阔的战场，包括不同的区域、建筑和资源分布。玩家需要利用自己的智慧和战术，探索地图并收集武器、装备和资源。地图边界会逐渐缩小，玩家需要不断向安全区域移动，避免被边界淘汰。

#### 生存阶段
当地图缩小到一定程度后，所有玩家将被迫进入一起战斗。在生存阶段中，玩家需要利用自己收集到的武器和装备，与其他玩家展开激烈的战斗，直到最后只有一个玩家存活下来。地图边界会继续缩小，玩家需要不断向安全区域移动，避免被边界淘汰。


#### 引擎
本分支游戏采用fyrox引擎进行开发


#### 编程语言
本游戏采用Rust语言进行开发。

### 总结：
这是诸神之战策划书大纲，包括游戏概念、玩法、角色设定、关卡设计等方面的内容。


## 运行
### 启动编辑器 
```bash
cargo run --package editor --release
```

### 运行游戏
```bash
cargo run --package executor --release
```