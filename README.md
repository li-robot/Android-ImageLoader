
#**概述**

该目录下为自己定义的一些工具类，现在只实现了一个Android图片加载工具ImageLoader，该工具使用了LRUCache技术，能够有效防止OOM，支持本地缓存，图片压缩等功能，能够满足开发中图片加载的基本需求，该工具只有一个java文件，使用简便，容易扩展，不需要导入一些冗余的第三方jar包


- 示例代码：

```java
ImageLoader loader = new ImageLoader();
loader.load(image, "http://XXX") // 支持本地和网络地址
```