FFmpeg README FFmpeg 使用必读
=============================

FFmpeg is a collection of libraries and tools to process multimedia content
such as audio, video, subtitles and related metadata.
这就是个处理多媒体的工具和库的集合。

## Libraries

* `libavcodec` provides implementation of a wider range of codecs.
* `libavcodec` ====-提供更广泛的编解码器的实现
* `libavformat` implements streaming protocols, container formats and basic I/O access.
* `libavformat` 实现的流协议，容器的格式和基础I/O访问
* `libavutil` includes hashers, decompressors and miscellaneous utility functions.
* `libavutil` 包含hash计算器，解压器和杂七杂八的工具函数
* `libavfilter` provides a mean to alter decoded Audio and Video through chain of filters.
* `libavfilter` 提供通过过滤器链改变解码的音频和视频的方法
* `libavdevice` provides an abstraction to access capture and playback devices.
* `libavdevice` 提供一个提供访问捕获和回放设备的抽象。
* `libswresample` implements audio mixing and resampling routines.
* `libswresample` 实现音频混合和重采样例程
* `libswscale` implements color conversion and scaling routines.
* `libswscale` 实现颜色转换和缩放样例

## Tools

* [ffmpeg](https://ffmpeg.org/ffmpeg.html) is a command line toolbox to
  manipulate, convert and stream multimedia content.
  一个操作，转换和流式传输多媒体命令行工具箱。
* [ffplay](https://ffmpeg.org/ffplay.html) is a minimalistic multimedia player.
  一个简约的多媒体播放器。
* [ffprobe](https://ffmpeg.org/ffprobe.html) is a simple analysis tool to inspect
  multimedia content.
  一个简单的检查多媒体内容的分析工具
* Additional small tools such as `aviocat`, `ismindex` and `qt-faststart`.
  一些额外的小工具比如，aviocat，ismindex 和 qt-faststatr

## Documentation

The offline documentation is available in the **doc/** directory.

The online documentation is available in the main [website](https://ffmpeg.org)
and in the [wiki](https://trac.ffmpeg.org).

### Examples

Coding examples are available in the **doc/examples** directory.

## License

FFmpeg codebase is mainly LGPL-licensed with optional components licensed under
GPL. Please refer to the LICENSE file for detailed information.

## Contributing

Patches should be submitted to the ffmpeg-devel mailing list using
`git format-patch` or `git send-email`. Github pull requests should be
avoided because they are not part of our review process and will be ignored.
