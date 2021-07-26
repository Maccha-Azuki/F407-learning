# working with MATLAB

![](assets/markdown-img-paste-20210724120054478.png)

![](assets/markdown-img-paste-20210724120107751.png)

![](assets/markdown-img-paste-20210724120133715.png)

256=255**+1**


![](assets/markdown-img-paste-20210724120406582.png)

![](assets/markdown-img-paste-20210724120602626.png)

![](assets/markdown-img-paste-20210724120651155.png)

- 之后在CubeMX中配置相关选项,包括:
    - ADC(input)
    - DAC(output)
    - 和一些时钟

![](assets/markdown-img-paste-20210724121850473.png)

接下来配置ADC和DAC, 全部都按正常配置就可以.

![](assets/markdown-img-paste-20210724122434553.png)

![](assets/markdown-img-paste-20210724122522112.png)

要是有特殊需求(高采样)也可以用DMA多通道连续采, 这里没必要


![](assets/markdown-img-paste-20210724122712965.png)

↑ DAC, 不用NVIC也不用DMA, 就输出
