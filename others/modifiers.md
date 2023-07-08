
## 修改器
+ select -> 右侧扳手图标 -> add modifier
+ `ctrl A` 应用修改器
+ `ctrl 2` 添加 subdivision modifier
    + 

## modifiers
+ subdivision
    + 用于增加模型的细分细节和光滑度。它通过对模型的几何结构进行分割和插值来实现这一目的。
    + 有时候细分后的几何结构可能会导致一些意外的变形，特别是在模型的边缘或锐角处。在这种情况下，你可以使用边缘环（Crease）来保持锐角的定义或添加支撑边（Support Edge）来控制细分的流向。

+ solidify
    + 平面加厚度

+ simple deform
    + 变弯
    + 锥化

+ bevel

+ Boolean
    + 不同物体重叠部分去交集，差集，并集


## tips
+ 修改器生效方式从上到下
    + 顺序影响结果

## ref
+ [Introduction](https://docs.blender.org/manual/en/3.0/modeling/modifiers/introduction.html#bpy-types-modifier-name)