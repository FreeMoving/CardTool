# CardTool
一个轻量级图片批量拼接工具。

该工具是我在MacOS开发学习之路上的周边产物。目的是要将，需要在ps中多步骤处理的图片，在工具中一步完成。并且可以批量化进行。

目前实现的功能：
总体实现：在一个“bg”图片中，嵌入“abcd”四个icon。且将“素材路径”中的图片，作为“bg”，重复abcd四个图片的批量嵌入。


分功能：
  1.获取icon在bg中的绝对位置，用于辅助。
  2.获取素材、icon的文件路径。
  3.批量获取素材path中的图片，作为bg，重复进行任务。
