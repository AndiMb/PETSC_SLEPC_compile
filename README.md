# How to compile PETSc/SLEPc with MUMPS as squential static library under Windows

## Preparation
1. Download Visual Studio Community (https://visualstudio.microsoft.com/de/downloads/)
2. Install Visual Studio Community (Hint: If the OS language is different than English, do install [only] English. Otherwise all compiler language are not in english an the filter during PETSc configuration will not work.)
3. Download and Install Intel oneAPI Base Toolkit - MKL (https://www.intel.com/content/www/us/en/developer/tools/oneapi/toolkits.html)
4. Download and Install Intel oneAPI HPC Toolkit - classic C/C++ and FORTRAN compiler (https://www.intel.com/content/www/us/en/developer/tools/oneapi/toolkits.html)
5. Install Cygwin (https://www.cygwin.com/install.html) with wget, make, python3, git
6. Start > Intel oneAPI 2022 > Intel oneAPI command prompt for Intel 64 for Visual Studio 2022. This should start a “dos cmd” shell.
7. Within this shell - run Cygwin terminal/bash-shell mintty.exe as:
```
C:\cygwin\bin\mintty.exe
```
8. check PATH environment variable 
