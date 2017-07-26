# 事件

事件类: 以下函数为hook函数, 当游戏执行到以下事件便会执行对应的函数

---

* ### 添加技能按钮 \[文本\]

  * 添加一个名字为 \[文本\] 的按钮到屏幕上, 在该积木之下的事件为点击按钮后执行的事件
* ### 当方块被点击
* * function useItem \(x, y, z, itemId, blockId, side, itemDamage, blockDamage\)
  * 参数
    * x, y, z
    * itemId : 手持物品ID
    * blockId : 被点击方块ID
    * side : 被点击的面
    * itemDamage : 手持物品信息
    * blockDamage : 被点击方块信息 
* ### 当方块被破坏

  * function destroyBlock \(x, y, z, side\)

  * 参数

    * x, y, z

    * side : 被点击的面
* ### 当开始破坏方块

  * function startDestroyBlock \(x, y, z, side\)
  * 参数
    * x, ,y ,z
    * side : 被点击的面
* ### 当初始化游戏

  * function newLevel\(\)
* ### 当离开游戏

  * function leaveGame\(\)
* ### 当实体被攻击

  * function attackHook\(attacker, victim\)

  * 参数

    * attacker :  攻击者

    * victim :  被攻击者
* ### 当投掷物砸中实体

  * function projectileHitEntityHook\(projectile, target\)

  * 参数

    * projectile : 投掷物

    * target : 被砸中实体
* ### 当投掷物砸中方块

  * function projectileHitBlockHook\(Projectile, blockX, blockY, blockZ, side

  * 参数

    * Projectile : 投掷物

    * blockX,** **blockY, blockZ : 坐标

    * side : 被砸中的面
* ### 当爆炸发生

  * function explodeHook\(ent, x, y, z, power, onFire\)

  * 参数

    * ent : 爆炸物

    * power : 爆炸范围

    * onFire : 是否着火
* ### 当玩家有吃的项

  * function eatHook\(hearts, saturationRatio\)
* ### 当实体已经遭受损害

  * function entityHurtHook\(attacker, victim, hearts\)

  * 参数

    * attacker :  攻击者

    * victim :  被攻击者

    * hearts : 伤害值
* ### 当玩家拿起经验球

  * function playerAddExpHook\(player, experienceAdded\)

  * 参数

    * player : 捡起经验球的实体

    * experienceAdded : 获取的经验值多少; 大经验球:7, 中经验球:3,小经验球:1
* ### 循环调用

  * 该函数每0.05秒调用一次

  * function modTick\(\)
* ### 当发送聊天信息

  * function chatHook\(text\)

  * 参数

    * text : 消息内容
* ### 当输入命令

  * function procCmd \(cmd\)

  * 参数

    * cmd : 指令
* ### 当实体死亡

  * function deathHook\(attacker, victim\)
  * 参数
    * attacker : 攻击者
    * victim : 被攻击者
* ### 当实体消失

  * function entityRemovedHook\(entity\)

  * 参数

    * entity : 实体
* ### 当添加实体

  * function entityAddedHook\(entity\)

  * 参数

    * entity: 实体
* ### 当收到消息

  * function chatReceiveHook\(str, sender\)

  * 参数

    * str : 消息内容

    * sender : 发送人

### 



