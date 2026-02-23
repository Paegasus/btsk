Commands to generate the solution and build it:

"C:\Program Files (x86)\Microsoft Visual Studio\2022\BuildTools\VC\Auxiliary\Build\vcvars64.bat"

mkdir build

cmake -G "Visual Studio 17 2022" -A x64 -S . -B build

cmake --build . --config Debug

cmake --build . --config Release