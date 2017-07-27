# 玩家

玩家类 : 执行所有与玩家有关的事件

---

#### 设置玩家血量为 \[数值\]

![](/assets/玩家/设置玩家血量为x.png)

Player.setHealth\(health\)

#### 焦点 \[X/Y/Z\] 坐标

![](/assets/玩家/玩家x坐标.png)

Player.getPointedVecX\(\)

Player.getPointedVecY\(\)

Player.getPointedVecZ\(\)

#### 焦点坐标

![](/assets/玩家/焦点坐标.png)

\(Player.getPointedVecX\(\),Player.getPointedVecY\(\),Player.getPointedVecZ\(\)\)

#### 焦点实体

![](/assets/玩家/焦点实体.png)

Player.getPointedEntity\(\)

返回准星所指向的实体

#### 玩家

![](/assets/玩家/玩家.png)

Player.getEntity\(\)

#### 玩家手持物品

![](/assets/玩家/玩家手持物品.png)

Player.getCarriedItem\(\)

#### 手中物品数量

![](/assets/玩家/手中物品数量.png)

Player.getCarriedItemCount\(\)

#### 手中物品信息

![](/assets/玩家/手中物品信息.png)

Player.getCarriedItemData\(\)

#### 玩家 \[X/Y/Z\] 坐标

![](/assets/玩家/玩家x坐标.png)

Player.getX\(\)

Player.getY\(\)

Player.getZ\(\)

#### 玩家坐标

![](/assets/玩家/玩家坐标.png)

\(Player.getX\(\),Player.getY\(\),Player.getZ\(\)\)

#### 玩家名称

![](/assets/玩家/玩家名称.png)

Player.getName\(playerName\(defalut : Player.getEntity\(\)\)

#### 判断 \[实体\] 是否是玩家

![](/assets/玩家/判断x是否是玩家.png)

Player.isPlayer\(entity\)

#### 选中的物品栏中的物品ID

![](/assets/玩家/选中的物品栏中的物品id.png)

Player.getSelectedSlotId\(\)

#### 物品栏第 \[数值\] 的物品ID

![](/assets/玩家/物品栏第x的物品ID.png)

Player.getInventorySlot\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 物品栏第 \[数值\] 的物品数量

![](/assets/玩家/物品栏第x的物品数量.png)

Player.getInventorySlotCount\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 物品栏第 \[数值\] 的物品信息

![](/assets/玩家/物品栏第x的物品信息.png)

Player.getInventorySlotData\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 添加 \[数值\] 个 \[物品\] 到物品栏

![](/assets/玩家/添加x个xx到物品栏.png)

Player.addItemCreativeInv\(id, count\)

#### 添加 \[数值\] 个 \[物品\] 到背包

![](/assets/玩家/添加x个xx到背包.png)

Player.addItemInventory\(id, count\)

#### 设置玩家 \[是/否\] 飞

![](/assets/玩家/设置玩家成立飞.png)

Player.setCanFly\(canFly\)

#### 玩家 \[是/否\] 在飞

![](/assets/玩家/玩家成立在飞.png)

Player.setFlying\(setFly\)

#### 设置物品栏第 \[数值\] 个位置为 \[物品\]

![](/assets/玩家/设置物品栏第x个位置为xx.png)

Player.setArmorSlot\(slot, id\)

slot : 代表第几个格子, 限制 0~44

#### 删除第 \[数值\] 个物品栏的物品

![](/assets/玩家/删除第x个物品栏的物品.png)

Player.clearInventorySlot\(slot\)

slot : 代表第几个格子, 限制 0~44

### 自定义函数

* #### 玩家面对方向:返回玩家面对方向的方向名称

  * #### ![](/assets/玩家/玩家面对方向 .png)
* * #### West 西边
  * #### North West 西北边
  * #### North 北边
  * #### North East 东北边
  * #### East 东边
  * #### South East 东南边
  * #### South 南边
  * #### South West 西南边



