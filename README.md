# canvas 元素 API

只有两个属性三个方法

## 属性

- width: 非负整数 默认 300， 如果只设置 style width会导致绘图表面缩放
- height: 非负整数 默认 150， 如果只设置 style height会导致绘图表面缩放

## 方法

- getContext()。
- toDataUrl(type='image/png', quality=1.0): 返回数据地址（data URL），可以设为 img 的 src。type指定图像格式; quality 为 0-1.0 的 double值。
- toBlob(callback, type='image/png', quality=1.0): 创建一个用于表示此 canvas元素图像文件的Blob。浏览器会用一个指向 blob 的引用为参数调用 callback。
