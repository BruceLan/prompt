# 图片框架 (Image)

高效加载、缓存和显示网络或本地图片。

-   **cached_network_image**: Flutter社区最主流的网络图片加载和缓存库。提供了强大的缓存机制，并支持自定义占位符（Placeholder）和错误组件（Error Widget）。
-   **Image.network**: Flutter内置的构造函数，用于直接从URL加载图片。简单直接，但默认没有提供磁盘缓存策略，每次都需要重新从网络获取。
-   **flutter_svg**: 专门用于在Flutter应用中渲染SVG（可缩放矢量图形）格式的图片。对于需要无损缩放的图标和插图来说是必不可少的。
-   **extended_image**: 一个功能强大的图片库，除了基础的加载和缓存，还内置了图片裁剪、编辑、缩放/拖动手势支持等高级功能。
