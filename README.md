julia-64-build-with-mingw-builds-for-R is julia build for win64, this build is for R and rjulia support.

build toolchain is msys2 + mingw-builds 4.9.2 x86_64 rev3, julia is release-0.4 branch. in this build openblas build with haswell cpu, if your cpu is older than it, rename bin\libopenblas64_.dll.old (this is dll in offical julia 0.4.1 release)  to bin\libopenblas_64.dll.

and copy zlib1.dll to bin after extract 7z file
