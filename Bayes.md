A|B 用编程语言表示为 `A = model_image_to_text(B)`

B|A 用编程语言表示为 `B = model_text_to_image(A)`

则贝叶斯公式
`P(A|B) = P(B|A)P(A)/P(B)`

被表示为

`P(model_image_to_text(B)) = P(model_text_to_image(A)) * P(A) / P(B)`

即我们如果知道了`model_text_to_image`模型的正确率，观测到了P(A)和P(B)发生的统计，那么可以推导出`model_image_to_text`模型的大致效果
