Tested with Graphviz version 2.24,2.26.3

Install graphviz and include C:\Program Files\Graphviz\bin into PATH or just copy graphviz dll's into project output directory, required dll's:
  * cdt.dll
  * graph.dll
  * gvc.dll
  * gvcplugin\_core.dll
  * gvcplugin\_dot\_layout.dll
  * libexpat.dll
  * ltdl.dll
  * Pathplan.dll
  * regex\_win32.dll
  * and config6(see config6.sample)

GraphVizNet is Visual C++ project, if you don't have installed Visual C++, you can use precompiled version of GraphVizNet.dll in ["Precompiled" folder.](http://code.google.com/p/graphviznet/source/browse/Precompiled/GraphVizNet.dll)

Add C:\Program Files\Graphviz\include\graphviz to include search path and C:\Program Files\Graphviz\lib\release\lib to library search path(For VS2008: Tools->Options->Projects and Solutions->VC++ Directories).