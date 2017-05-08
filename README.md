# GloVe-win
Stanford GloVe(https://github.com/stanfordnlp/GloVe) tools built for windows compiled with visual studio 2017 and dev c++ on Windows 10 x64.

You could just download a release(https://github.com/anoidgit/GloVe-win/releases) and run it on Windows as the same way on linux.

If you have a large mount of parameters to train(a large number of words or high dimension of embeddings) which means you will need a large amount of memory to use, you'd better use the 64-bit version if the 32-bit version can not work, but for most of the time, 32-bit version is just enough to work.

For files built with Visual Studio 2017, you should have Visual C++ Redistributable for Visual Studio 2017(https://www.microsoft.com/en-us/download/details.aspx?id=48145) installed in your system. For Windows version smaller than 10, you may need to install Universal C Runtime(https://support.microsoft.com/zh-cn/help/2999226/update-for-universal-c-runtime-in-windows) before you install the Visual C++ Redistributable for Visual Studio 2017.

You could also try the files built with dev c++, which are more universal and can easily run on many windows with different version.

You could try to compile these C code your self with POSIX Threads (pthreads) for Win32(http://sourceware.org/pthreads-win32/) if you want.
