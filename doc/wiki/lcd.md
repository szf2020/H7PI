#### LCD接口
LCD接口用于驱动我们常见的TFT液晶屏，采用告诉FSMC内存接口，FSMC接口可以达到240MHz，操作时就像是操作内存一样方便

#### 8Bits FSMC
为了达到更小的接口和更少的pin，采用8bits接口，虽然速度会相对16bits接口减半，但是同样可以支持565等常用接口，同时因为采用FSMC接口，高速驱动足以覆盖位数带来的减速。

#### FPC接口
FPC采用24pins，pitch 0.5mm，上接，可以直接兼容IL9341,8bits并口,2.8寸TFT（240x320）。
