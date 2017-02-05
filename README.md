# GloVe-win
Stanford GloVe(https://github.com/stanfordnlp/GloVe) tools built for windows compiled with visual studio 2015 on Windows 10 x64.

You could just download a release(https://github.com/anoidgit/GloVe-win/releases) and run it on Windows as the same way on linux.

If you have a large mount of parameters to train(a large number of words or high dimension of embeddings) which means you will need a large amount of memory to use, you'd better use the 64-bit version if the 32-bit version can not work, but for most of the time, 32-bit version is just enough to work.

Because it was built with Visual Studio 2015, you should have Visual C++ Redistributable for Visual Studio 2015(https://www.microsoft.com/en-us/download/details.aspx?id=48145) installed in your system. For Windows version little than 10, you may need to install Universal C Runtime(https://support.microsoft.com/zh-cn/help/2999226/update-for-universal-c-runtime-in-windows) before you install the Visual C++ Redistributable for Visual Studio 2015.

You could also try to rebuild the binary executable file with Dev C++ or previous version of visual studio based on the C code in project repository and POSIX Threads (pthreads) for Win32(http://sourceware.org/pthreads-win32/) in case you do not want to install the system components.
