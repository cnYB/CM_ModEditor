# 世界

世界类: 执行所有跟世界有关的事件

---

#### 在聊天框显示文本 \[文本\]

![](/assets/世界/在聊天框显示文本.png)

clientMessage\(text\)

#### 弹出文本 \[文本\]

![](/assets/世界/弹出文本.png)

print\(text\)

#### 在 \[坐标\] 的地方产生半径 \[数值\] \[着火/不着火\] 的爆炸

![](/assets/世界/在xx的地方产生半径xx的爆炸.png)

Level.explode\(x, y, z, radius,fire\)

#### 在 \[坐标\] 放置 \[数值\] 个 \[物品\]

![](/assets/世界/在xx放置x个xx.png)

Level.dropItem\(x, y, z, id, amount\)

#### 设置 \[坐标\] 的方块为 \[物品\]

![](/assets/世界/设置xx的方块为xxx.png)

Level.setTile\(x, y, z, id\)

#### 粒子效果 \[粒子效果\], 在位置 \[坐标\]

![](/assets/世界/粒子效果在位置xx.png)

Level.addParticle\(id, x, y, z\)

#### 获取 \[坐标\] 方块ID

![](/assets/世界/获取xx方块id.png)

Level.getTile\(x, y, z\)

#### 我的世界名称

![](/assets/世界/我的世界名称.png)

Level.getWorldName\(\)

#### 设置游戏时间为 \[数值\]

![](/assets/世界/设置游戏时间.png)

Level.setTime\(time\)

time 限制 : 0~24000

#### 游戏的时间

![](/assets/世界/游戏的时间.png)

Level.getTime\(\)

#### 设置游戏模式为 \[上帝模式/生存模式\]

![](/assets/世界/设置游戏模式.png)

Level.setGameMode\(gamemode\)

#### 游戏模式

![](/assets/世界/游戏模式.png)

Level.getGameMode\(\)

#### 设置 \[夜间模式/非夜间模式\]

![](/assets/世界/设置夜间模式.png)

Level.setNightMode\(isNight\)

#### 设置玩家在 \[坐标\] 出生

![](/assets/世界/设置玩家在xx位置出生.png)

Level.setSpawn\(x, y, z\)

#### 获取 \[坐标\] 发光强度

![](/assets/世界/获取xx的发光强度.png)

Level.getBrightness\(x, y, z\)

#### 在 \[坐标\] 生成 \[生物\]

![](/assets/世界/在xx生成xxx.png)

Level.spawnMob\(x, y, z, typeId\)

#### 忽略该函数原本功能

![](/assets/世界/忽略该函数原本功能.png)

preventDefault\(\)

该函数作用是用于忽略hook函数原本的功能, 例如在startDestroyBlock\(当开始破坏方块\)函数中添加preventDefault\(\), 则被破坏的方块不会受到伤害.

#### 破坏 \[坐标\] 方块, 方块 \[是/否\] 掉落

![](/assets/世界/破坏xx方块，方块xx掉落.png)

Level.destroyBlock\(x, y, z, shouldDrop\)

### 自定义函数

* #### 在 \[坐标\] 使用 \[方块\] 生产长 \[数值\] 宽 \[数值\] 高 \[数值\] 的长方体

  * #### ![](/assets/世界/在xx使用xx生成长宽高xx的长方体.png)
* #### 在 \[坐标\] 使用 \[方块\] 生成半径为 \[数值\] 的球

  * #### ![](/assets/世界/在xx使用xx生成半径为x的球.png)



