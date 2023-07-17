The Directory for the custom UNIX shell. The folder structure is as follows:

1, inc : This folder contains all the header definitions for the shall to be used.

2, src : The main entry point as well as auxillary function bodies will be here.

3, out : The folder wherein the artifacts of the build process shall be stored.
         There will be an out of source build.
         A support for debug as well as release builds shall be integrated.

4, tool : The folder will contain all the tooling required for the project.
          - nm parsing invoker
          - debugger GDB script
          - ctags script
          - possibel recursive make as well
          - linker Script
          - Profiling tool configurations

5, test : Boundary as well as full program tests will be here.

6, env.sh : The bash script that sets up the environment for the programs as well as
            fetching right packages for the envrionment if not installed.

7, makefile : simple script functioning as a job runner a build tool for fine-grained
            build with separate compilation. Out of source build with sub-directories
            for libraries and source will be developed.

8, lib : verified functionalities for example form other branches will be appended here.

9, license : file containing licensing details for the tool