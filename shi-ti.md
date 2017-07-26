# 实体

实体类 : 执行所有与实体有关的事件

---

#### 让 \[实体\] 乘坐到 \[实体\] 上

Entity.rideAnimal\(rider, mount\)

#### 设置 \[坐标\] 着火 \[数值\] 秒

Entity.setFireTicks\(entity, howLong\)

#### 当前世界中所有的实体

Entity.getAll\(\)

返回世界总所有实体的数组

#### 获取 \[实体\] 类型

Entity.getEntityTypeId\(entity\)

#### 设置 \[实体\] 的最大生命值为 \[数值\]

Entity.setMaxHealth\(entity,maxHealth\)

#### 设置 \[实体\] 的生命值为 \[数值\]

Entity.setHealth\(entity, health\)

#### 获取 \[实体\] 的生命值

Entity.getHealth\(entity\)

#### 设置 \[实体\] 的 \[X/Y/Z\] 方向加速度为 \[数值\]

Entity.setVelX\(entity, amount\)

Entity.setVelY\(entity, amount\)

Entity.setVelZ\(entity, amount\)

#### 获取 \[实体\] 的 \[X/Y/Z\] 方向加速度

Entity.getVelX\(entity\)

Entity.getVelY\(entity\)

Entity.getVelZ\(entity\)

#### 移动 \[实体\] 到 \[坐标\]

Entity.setPosition\(entity,x,y,z\)

#### 获取 \[实体\] 的皮肤

Entity.getMobSkin\(entity\)

#### 获取 \[实体\] 的名称

Entity.getNameTag\(entity\)

#### 获取 \[实体\] 的 \[X/Y/Z\] 坐标

Entity.getX\(entity\)

Entity.getY\(entity\)

Entity.getZ\(entity\)

#### 获取 \[实体\] 的水平方向旋转角度

Entity.getYaw\(entity\)

#### 获取 \[实体\] 的垂直方向旋转角度

Entity.getPitch\(entity\)

#### 添加 \[数值\] 秒 \[药水效果\] 到 \[实体\]

Entity.addEffect\(entity, effect\_id, effect\_time\)

effect\_time : 时长; 时长 = 秒 \* 20;

例如:添加5秒效果时长:5\*20=100

#### 移除 \[实体\] 所有特效

Entity.removeAllEffects（entity\)

#### 移除 \[实体\]

Entity.remove\(entity\)

#### 获取 \[实体\] 年龄

Entity.getAnimalAge\(entity\)

#### 设置 \[实体\] 的年龄为 \[数值\]

Entity.setAnimalAge\(entity, age\)

age : 年龄; 0:成年, -24000:幼年

#### 设置 \[实体\] 手中物体为 \[物品\]

Entity.setCarriedItem\(entity, id\)

#### 设置 \[实体\] 名称为 \[文本\]

Entity.setNameTag\(entity, name\)

#### 移动 \[实体\] 到相对当前 \[坐标\]

Entity.setPositionRelative\(entity, x, y, z\)

#### 设置 \[实体\] 水平角度为 \[数值\] 垂直角度为 \[数值\]

Entity.setRot\(entity, yaw, pitch\)

#### 设置 \[实体\] \[是/否\] 潜行

Entity.setSneaking\(entity, isSneaking\)

