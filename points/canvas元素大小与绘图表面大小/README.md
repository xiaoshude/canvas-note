# canvas 元素实际上有两套尺寸。

- 元素本身的大小
- 元素绘图表面的大小（drawing surface）

## canvas 元素的 width/height 与 style 的 width/height

- 设置元素的 width/height 会同时设置上面两种大小
- 设置style 的 width/height 只会设置元素的本身的大小。而且糟糕的是：浏览器还会缩放【元素绘图表面的大小】来适应【元素本身的大小】。这个可能会导致变形。具体见见示例。

tip: 

- canvas元素的默认 width/height 为 300/150
- canvas元素的默认 width/height 使用不带 px 后缀的非负整数，设置 style 时需要带px的字符串。

