# 测试 MC_04 -故障安全测试

❏ 验证 RC Loss 动作是否返回陆地

❏ 验证数据链路丢失操作返回陆地，超时是10秒

❏ 验证电池是否安全

&nbsp;&nbsp;&nbsp;&nbsp;❏ Action is Return to Land

&nbsp;&nbsp;&nbsp;&nbsp;❏ Battery Warn Level is 25%

&nbsp;&nbsp;&nbsp;&nbsp;❏ Battery Failsafe Level is 20%

&nbsp;&nbsp;&nbsp;&nbsp;❏ Battery Emergency Level is 15%

❏ 在高度模式下起飞

❏ 离开原位至少 20 米

❏ RC 损失

&nbsp;&nbsp;&nbsp;&nbsp;❏Turn off RC and check the vehicle returns to home position, wait for the descent and turn on the RC and take over.

## 数据链路丢失

❏ 断开遥测，车辆应在 10 秒后返回原位，等待下降并重新连接遥测无线电

## 切换到高度模式

❏ 确保横滚，俯仰和偏航杆像稳定模式一样响应

❏ 节流阀应控制高度，当操纵杆居中时，必须保持高度

## 切换到位置模式

❏ 当棒居中时，它必须保持位置

❏移动横滚，俯仰和偏航，并根据输入检查无人机是否在移动

❏ 再次将木棒对中并检查无人机是否保持位置

## 电量故障保护触发器

❏ 确认 QGC 收到警告信息

❏ 确认无人机返回降落状态

❏ 确认车辆着陆。
