# Regen
Regen is an intuitive in-code templating engine based on a C#-Python like regen-lang created to replace T4 Templating.<br>
Regen as a template compiler/engine allows to expand in-line templates to be compiled into C# code and inserted into the same source file.<br>
It is mainly used to generate repetitive code - for instance the efficient handling of primitive types without boxing requires a branch for every type that executes the same operation. 

**Current version:** 0.27a-2<br>

### Installation
Regen is shipped as a visual studio extension (VSIX) and currently supports `vs2017` and `vs2019`.<br>
Official releases can be downloaded [here](https://github.com/Nucs/Regen/tree/master/releases) or in the [releases page](https://github.com/Nucs/Regen/releases).<br>

### Getting Started
Regen provides a handy Visual Studio plugin which compiles embedded `regen-lang` templates in your C# source files. 
For an in-depth language introduction, make sure to read our [getting started](TUTORIAL.md) page!
<p align="center">
  <img align="center" src="resources/quickexample.gif" height=300 width=420 />
  <img align="center" src="resources/quickexample-2.gif" height=300 width=420 />
</p>

### Contributions
Contributions are welcome, if you would like to help: check out our [TODO page](TODO.md).<br>
Thought about a new feature that might come handy? Create an issue about it and get started!

**Expectations**<br>
- Any new feature is expected to be fully tested.
- Any new code is expected to be formatted according to the file it is in or exactly like the neighbor files.


### Powered by Regen
These libraries heavily rely on Regen to generate repetitive code:
* [NumSharp](https://github.com/SciSharp/NumSharp)
* [Tensorflow.NET](https://github.com/SciSharp/Tensorflow.NET)
