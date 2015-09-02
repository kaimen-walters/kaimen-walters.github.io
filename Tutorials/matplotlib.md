
If you have Visual Studio installed, getting matplotlib in Pycharm is very easy.
Just go to File --> Settings
 
A new window, “Settings” will pop up. On the left hand side, expand “Project”, then click on Project Interpreter. If matplotlib is already installed, you will find it in this list of packages. If it’s not here, click on the “+” to add a package.


 ![project](https://cloud.githubusercontent.com/assets/12718302/8146307/3c8cd332-11f7-11e5-9d88-2fd36ec01023.jpg)

A new window, “Available Packages” will pop up. Start typing matplotlib in the search bar until you see it in the list. Highlight matplotlib and click on “Install Package” at the bottom. If you have the Visual Studio Compiler already installed, this package should install correctly and you’ll be done. If you’re like me, and don’t have Visual Studio, you will get the following error or something similar:
 “error: unable to find vcvarsall.bat”

![add_package](https://cloud.githubusercontent.com/assets/12718302/8146310/5349c8dc-11f7-11e5-87c7-a34341e3a83b.jpg)


If you don't already have Visual Studio, it is a bit more involved but still easily done.

Without Visual Studio, you will have to find a distribution of Python that comes with the matplotlib package(and others) built and loaded. I used WinPython ( http://sourceforge.net/projects/winpython/ ) but there are others you can use like Canopy ( https://www.enthought.com/products/canopy/ ) or Anaconda ( https://store.continuum.io/cshop/anaconda/ ). Download and install your preferred distribution in a directory in your main drive (mine went in C:\WinPython\  by default). 
Once your distribution is installed, open Pycharm. Go to File -> Settings. A new window, "Settings",  will pop up. Expand the "Projects" menu along the left side and click on "Project Interpreter". 
![winpython](https://cloud.githubusercontent.com/assets/12718302/8146443/aaa12f48-11fd-11e5-9c47-bff9f2fce438.jpg)

In that circled area, put in the file-path to the " python.exe " file inside the distribution you installed. It may not be exactly the same as shown in the picture but it should still end with " python.exe ".

After this is done, it may take a few minutes for Pycharm to reconfigure. It may not be required but I think it's a good idea to close Pycharm and restart it at this point. Now you can 'import' the necessary libraries at the top of your *.py file. See the documentation at http://matplotlib.org/contents.html for help with matplotlib commands and tools. 

Hope this helps.


