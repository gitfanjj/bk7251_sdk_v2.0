# voice_config 2.0 Change Log

## 2.0.0

* 优化算法，不再需要同步头。
* 数据倒序，把长度放在最末尾，以降低自动匹配时的运算量。
* 字节拆分时，高位在前，以方便调试时辨认。
* 更新上位机工具
 - 数据倒序（需要重新部署到服务器）
 - 使用固定参数数量

# voice_config 1.0 Change Log

* 对同步头进行16次匹配，使同步点更加精确。
