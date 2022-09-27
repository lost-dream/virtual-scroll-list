# props

|       props       |                                       desc                                        |  default   |
| :---------------: | :-------------------------------------------------------------------------------: | :--------: |
|       width       | 滚动列表的宽度, 默认值 100%. 当滚动方向为水平滚动时必填(需要确定的宽度计算相关值) |   `100%`   |
|      height       | 滚动列表的高度, 默认值 100%. 当滚动方向为垂直滚动时必填(需要确定的宽度计算相关值) |   `100%`   |
|       data        |                                虚拟列表数据，必填                                 |     -      |
|  scrollDirection  |                                     滚动方向                                      | `vertical` |
| scrollToAlignment |                  配合 scrollToIndex 使用, 控制当前焦点的对齐方式                  |   `auto`   |
|      buffer       |            在显示内容之外预加载的缓冲列表项个数，用来优化滚动时的效果             |     4      |
|     itemSize      |   列表项的高度/宽度(取决于滚动方向), 必填. 可以是具体的数字或返回给定高度的函数   |     -      |
|   scrollOffset    |                                 设置滚动的偏移量                                  |     -      |
|   scrollToIndex   |                              设置滚动到列表项的索引                               |     -      |
