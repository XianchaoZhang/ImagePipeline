ImagePipeline 1.0
==============

ImagePipeline is a C++ API for designing OpenCV solutions through the use of pipelines rather than a set of specific functions. The inspiration came from spending lots of time meshing methods together to obtain efficient solutions preventing the use of repeating preprocessing steps, by using this API I can simply share the pipeline and when adding my ImageGraph (a set of preprocessing steps) to the pipeline it will make a tree representing the most efficient way of combining the graphs.

ImagePipeline 是一个 C++ API，用于通过使用管道而不是一组特定函数来设计 OpenCV 解决方案。 灵感来自于花费大量时间将网格划分方法结合在一起以获得有效的解决方案，防止使用重复的预处理步骤，通过使用此 API，我可以简单地共享管道，并且当我将 ImageGraph（一组预处理步骤）添加到管道时，它将制作一棵树，代表组合图表的最有效方式。

The example contains an implementation of the squares OpenCV demo program written in this way.

该示例包含以这种方式编写的正方形 OpenCV 演示程序的实现。

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0 "Apache License, Version 2.0")
Compiled and tested on OSX

Third party code
----------------

- [tree.hh](http://tree.phi-sci.com "tree.hh: an STL-like C++ tree class")

Dependencies
------------

- [opencv](http://opencv.willowgarage.com/wiki/ "OpenCV")
