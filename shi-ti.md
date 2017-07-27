# 实体

实体类 : 执行所有与实体有关的事件

---

#### 让 \[实体\] 乘坐到 \[实体\] 上

![](/assets/实体/让玩家乘坐到焦点实体上.png)

Entity.rideAnimal\(rider, mount\)

#### 设置 \[坐标\] 着火 \[数值\] 秒

![](/assets/实体/设置焦点实体着火3秒.png)

Entity.setFireTicks\(entity, howLong\)

#### 当前世界中所有的实体

![](/assets/实体/当前世界中的所有实体.png)

Entity.getAll\(\)

返回世界总所有实体的数组

#### 获取 \[实体\] 类型

![](/assets/实体/获取焦点实体类型.png)

Entity.getEntityTypeId\(entity\)

#### 设置 \[实体\] 的最大生命值为 \[数值\]

![](/assets/实体/设置焦点实体的最大生命值为10.png)

Entity.setMaxHealth\(entity,maxHealth\)

#### 设置 \[实体\] 的生命值为 \[数值\]

![](/assets/实体/设置焦点实体的生命值为.png)

Entity.setHealth\(entity, health\)

#### 获取 \[实体\] 的生命值

![](/assets/实体/获取焦点实体生命值.png)

Entity.getHealth\(entity\)

#### 设置 \[实体\] 的 \[X/Y/Z\] 方向加速度为 \[数值\]

![](/assets/实体/获取焦点实体的X方向的加速度.png)

Entity.setVelX\(entity, amount\)

Entity.setVelY\(entity, amount\)

Entity.setVelZ\(entity, amount\)

#### 获取 \[实体\] 的 \[X/Y/Z\] 方向加速度

![](/assets/实体/获取焦点实体的X方向的加速度.png)

Entity.getVelX\(entity\)

Entity.getVelY\(entity\)

Entity.getVelZ\(entity\)

#### 移动 \[实体\] 到 \[坐标\]

![](/assets/实体/移动焦点实体到位置.png)

Entity.setPosition\(entity,x,y,z\)

#### 获取 \[实体\] 的皮肤

![](/assets/实体/获取焦点实体皮肤.png)

Entity.getMobSkin\(entity\)

#### 获取 \[实体\] 的名称

![](/assets/实体/获取焦点实体的名称.png)

Entity.getNameTag\(entity\)

#### 获取 \[实体\] 的 \[X/Y/Z\] 坐标

![](/assets/实体/获取焦点实体的坐标.png)

Entity.getX\(entity\)

Entity.getY\(entity\)

Entity.getZ\(entity\)

#### 获取 \[实体\] 的水平方向旋转角度

![](/assets/实体/获取焦点实体的水平方向旋转角度.png)

Entity.getYaw\(entity\)

#### 获取 \[实体\] 的垂直方向旋转角度

![](/assets/实体/获取焦点实体的垂直方向旋转角度.png)

Entity.getPitch\(entity\)

#### 添加 \[数值\] 秒 \[药水效果\] 到 \[实体\]

![](/assets/实体/添加2秒药水效果到焦点实体.png)

Entity.addEffect\(entity, effect\_id, effect\_time\)

effect\_time : 时长; 时长 = 秒 \* 20;

例如:添加5秒效果时长:5\*20=100

#### 移除 \[实体\] 所有特效

![](/assets/实体/移除焦点实体所有特效.png)

Entity.removeAllEffects（entity\)

#### 移除 \[实体\]

![](/assets/实体/移除焦点实体.png)

Entity.remove\(entity\)

#### 获取 \[实体\] 年龄



Entity.getAnimalAge\(entity\)

#### 设置 \[实体\] 的年龄为 \[数值\]

![](/assets/实体/设置焦点实体年龄.png)

Entity.setAnimalAge\(entity, age\)

age : 年龄; 0:成年, -24000:幼年

#### 设置 \[实体\] 手中物体为 \[物品\]

![](/assets/实体/设置玩家手中物品为工具.png)

Entity.setCarriedItem\(entity, id\)

#### 设置 \[实体\] 名称为 \[文本\]

![](/assets/实体/设置焦点实体名称为.png)

Entity.setNameTag\(entity, name\)

#### 移动 \[实体\] 到相对当前 \[坐标\]

![](/assets/实体/移动焦点实体到相对当前位置.png)

Entity.setPositionRelative\(entity, x, y, z\)

#### 设置 \[实体\] 水平角度为 \[数值\] 垂直角度为 \[数值\]

![](/assets/实体/设置焦点实体水平角度为垂直角度为.png)

Entity.setRot\(entity, yaw, pitch\)

#### 设置 \[实体\] \[是/否\] 潜行

![](/assets/实体/设置焦点实体成立潜行.png)

Entity.setSneaking\(entity, isSneaking\)

