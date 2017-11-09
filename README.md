# 电子琴演示曲列表

YouTube 上的电子琴演示曲列表。

## JSON 格式

* `brand`：电子琴的厂商，比如 `Yamaha`、`Casio`
* `model`：电子琴的型号
* `range`：所包含演示曲的范围和位置，其作为一个数组存储：
  * `id`：演示曲序号，请以电子琴显示的为准
  * `position`：开始位置，如 `3:22`
* `quality`：录制品质。线路输入请填写 `line`，麦克风录制请填写 `mic`
* `link`：演示曲的 YouTube 视频地址，比如 `Ht9ffVVWddE`
