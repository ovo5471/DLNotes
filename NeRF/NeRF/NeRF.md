### Positional Encoding

NeRF **Positional Encoding**的公式：

<p style="text-align: center;">
<img src="1.png" width="400" height="50"/>
</p>

> it allows the MLP parameterizing the scene to behave as an interpolation function, where L determines the **bandwidth** of the interpolation kernel.

本质应该是傅里叶分解。