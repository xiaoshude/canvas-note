## Canvas 状态的保存和恢复

- save(): context 的 save方法会将当前的绘图环境压入堆栈顶端
- restore(): context 的 restore方法会弹出一组状态信息，并据此设置context的各个状态

注意：保存的是 context的各个属性，context函数的执行记录是没有，也就是不回保存绘制状态

## 绘制表面的保存和恢复

- getImageData()
- putImageData()

## 立即模式绘图系统和保留模式绘图系统

canvas 采用立即模式绘图，也就是它会立即将你制定的内容绘制到canvas上，然后立即忘记刚才绘制的内容。
-> canvas 不包含将要绘制图形对象的列表。

保留模式绘图系统则会

