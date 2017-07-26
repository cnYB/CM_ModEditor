# 世界

世界类: 执行所有跟世界有关的事件

---

#### 在聊天框显示文本 \[文本\]

clientMessage\(text\)

#### 弹出文本 \[文本\]

print\(text\)

#### 在 \[坐标\] 的地方产生半径 \[数值\] \[着火/不着火\] 的爆炸

Level.explode\(x, y, z, radius,fire\)

#### 在 \[坐标\] 放置 \[数值\] 个 \[物品\]

Level.dropItem\(x, y, z, id, amount\)

#### 设置 \[坐标\] 的方块为 \[物品\]

Level.setTile\(x, y, z, id\)

#### 粒子效果 \[粒子效果\], 在位置 \[坐标\]

Level.addParticle\(id, x, y, z\)

#### 获取 \[坐标\] 方块ID

Level.getTile\(x, y, z\)

#### 我的世界名称

Level.getWorldName\(\)

#### 设置游戏时间为 \[数值\]

Level.setTime\(time\)

time 限制 : 0~24000

#### 游戏的时间

Level.getTime\(\)

#### 设置游戏模式为 \[上帝模式/生存模式\]

Level.setGameMode\(gamemode\)

#### 游戏模式

Level.getGameMode\(\)

#### 设置 \[夜间模式/非夜间模式\]

Level.setNightMode\(isNight\)

#### 设置玩家在 \[坐标\] 出生

Level.setSpawn\(x, y, z\)

#### 获取 \[坐标\] 发光强度

Level.getBrightness\(x, y, z\)

#### 在 \[坐标\] 生成 \[生物\]

Level.spawnMob\(x, y, z, typeId\)

#### 忽略该函数原本功能

preventDefault\(\)

该函数作用是用于忽略hook函数原本的功能, 例如在startDestroyBlock\(当开始破坏方块\)函数中添加preventDefault\(\), 则被破坏的方块不会受到伤害.

#### 破坏 \[坐标\] 方块, 方块 \[是/否\] 掉落

Level.destroyBlock\(x, y, z, shouldDrop\)

### 自定义函数

* #### 在 \[坐标\] 使用 \[方块\] 生产长 \[数值\] 宽 \[数值\] 高 \[数值\] 的长方体
* #### 在 \[坐标\] 使用 \[方块\] 生成半径为 \[数值\] 的球



