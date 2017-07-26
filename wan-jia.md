# 玩家

玩家类 : 执行所有与玩家有关的事件

---

#### 设置玩家血量为 \[数值\]

Player.setHealth\(health\)

#### 焦点 \[X/Y/Z\] 坐标

Player.getPointedVecX\(\)

Player.getPointedVecY\(\)

Player.getPointedVecZ\(\)

#### 焦点坐标

\(Player.getPointedVecX\(\),Player.getPointedVecY\(\),Player.getPointedVecZ\(\)\)

#### 焦点实体

Player.getPointedEntity\(\)

返回准星所指向的实体

#### 玩家

Player.getEntity\(\)

#### 玩家手持物品

Player.getCarriedItem\(\)

#### 手中物品数量

Player.getCarriedItemCount\(\)

#### 手中物品信息

Player.getCarriedItemData\(\)

#### 玩家 \[X/Y/Z\] 坐标

Player.getX\(\)

Player.getY\(\)

Player.getZ\(\)

#### 玩家坐标

\(Player.getX\(\),Player.getY\(\),Player.getZ\(\)\)

#### 玩家名称

Player.getName\(playerName\(defalut : Player.getEntity\(\)\)

#### 判断 \[实体\] 是否是玩家

Player.isPlayer\(entity\)

#### 选中的物品栏中的物品ID

Player.getSelectedSlotId\(\)

#### 物品栏第 \[数值\] 的物品ID

Player.getInventorySlot\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 物品栏第 \[数值\] 的物品数量

Player.getInventorySlotCount\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 物品栏第 \[数值\] 的物品信息

Player.getInventorySlotData\(slot\)

slot : 代表第几个格子, 限制 0~44

#### 添加 \[数值\] 个 \[物品\] 到物品栏

Player.addItemCreativeInv\(id, count\)

#### 添加 \[数值\] 个 \[物品\] 到背包

Player.addItemInventory\(id, count\)

#### 设置玩家 \[是/否\] 飞

Player.setCanFly\(canFly\)

#### 玩家 \[是/否\] 在飞

Player.setFlying\(setFly\)

#### 设置物品栏第 \[数值\] 个位置为 \[物品\]

Player.setArmorSlot\(slot, id\)

slot : 代表第几个格子, 限制 0~44

#### 删除第 \[数值\] 个物品栏的物品

Player.clearInventorySlot\(slot\)

slot : 代表第几个格子, 限制 0~44

### 自定义函数

* #### 玩家面对方向

  * #### 返回玩家面对方向的方向名称
  * #### West 西边
  * #### North West 西北边
  * #### North 北边
  * #### North East 东北边
  * #### East 东边
  * #### South East 东南边
  * #### South 南边
  * #### South West 西南边



