#Mask RCNN for Object Detection
-------------------------------
A. Download Python 3.7.1  x64 executable file from the link : https://www.python.org/downloads/release/python-370/ 

B Download and extract the source tarball from Python 3.7.11 security and bug fix package from link : https://www.python.org/downloads/release/python-3711/, go to the readme file, click on the link on line 76 (https://github.com/python/cpython/blob/3.7/PCbuild/readme.txt).... follow the steps in (1a,2 and 3)

C. Download visuall c++ build tool ( https://visualstudio.microsoft.com/downloads/?q=build+tools ) it installs visual studio installer,

D. On installing it, ensure *Python native development* and *Desktop development with C++* component are selected.

E. Under the optional feature of *Desktop development with C++*, uncheck all except:MSVC v143, C++ ATL,Windows 10 SDK,C++ Profiling. This link should help on that ( https://devblogs.microsoft.com/cppblog/visual-studio-build-tools-now-include-the-vs2017-and-vs2015-msvc-toolsets/ )
	1.  Install Microsoft Visual Studio 2017 with Python workload and
    	Python native development component.
	1a. Open and extract the source tarball downloaded in B above,open folder PCBuild, 
	2.  Run "build.bat" to build Python in 64-bit Release configuration.
	3.  (Optional, but recommended) Run the test suite with "rt.bat -q".

F. Download wget from this- https://eternallybored.org/misc/wget/ 

G. Follow Installation steps here - https://builtvisible.com/download-your-website-with-wget/

H. Restart system

I. Unzip the project to the directory you want 

J. Install requirements.txt file ( pip install -r requirements.txt --user )

K. Open cmd prompt and install git : winget install --id Git.Git -e --source winget

L Run this on the command prompt: pip3 install "git+https://github.com/philferriere/cocoapi.git#egg=pycocotools&subdirectory=PythonAPI"

M. Open the file imagesPrediction.ipynb and run the cmd in sequenc
